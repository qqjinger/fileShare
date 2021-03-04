# fileShare
Temporary storage for big file share

# file's brief description  
## 1) 1-thread coremark riscv application without "-lpthread" option run on 1-core-smallboom config  
**1.1) coremark_1thread_NOlpthread.bare.riscv**  
      compile without the lpthread option and other options same.  
**1.2) coremark_1thread_NOlpthread.bare.objdump**  
      gcc compiler option without "lpthread" option, which run coreamrk correctly.  
    
## 2) 1-thread coremark riscv application with "-lpthread" option run on 1-core-smallboom config
**2.1) coremark_1thread_lpthread.bare.riscv**  
    compile with the lpthread option and other options same.  
**2.2) coremark_1thread_lpthread.bare.objdump**  
    gcc compiler option with "lpthread", whose other compiler options are same as "coremark_1thread_NOlpthread.bare.objdump".   
    When using riscv file corresponding to this objdump, boom simulator reports error message quickly.  
