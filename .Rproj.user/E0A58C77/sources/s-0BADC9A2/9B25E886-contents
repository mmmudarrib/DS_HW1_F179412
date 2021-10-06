# Reading Data from foo.txt into variable data
data <- read.table("foo.txt")
#Displaying Data variable
data
# Reading Data from foo.txt only first 100 rows into variable initial 
initial <- read.table("foo.txt", nrows = 100)
#Displaying Intial variable
initial
#getting classes of each column
classes <- sapply(initial, class)
# Reading Data from foo.txt only columns matching classes variable into variable taball 
tabAll <- read.table("foo.txt",
                     colClasses = classes)
classes
tabAll
