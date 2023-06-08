cmake_minimum_required(VERSION 3.0)
project(MyProject)
# Set the source files for your project
set(SOURCES calc.c)

# Set the header files for your project
set(HEADERS calc.h)

# Create the executable target
add_executable(MyProject ${SOURCES})



# Compile and link the first C file
#add_executable(executable1 calc.c calc.h)

# Compile and link the second C file
#add_executable(executable2 driver.c calc.h)

# Add more add_executable() commands for additional C files


