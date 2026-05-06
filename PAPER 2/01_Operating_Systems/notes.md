#### Mode bit 
 0 for kernel
1 for  user mode


*******************************************************************************

#### Threads shares  

1. Memory address space
2. Files
3. signals and their handles 

#### <mark>Threads do  not share</mark> 

1. Stack
2. Unique thread ID
3. Registers
4. Stack


*******************************************************************************

### User level vs Kernel level threads
NOTE:

1. User level threads are not recognized by kernel.
2. User level threads are dependent. Kernel level threads are independent.
3. User level threads can run one process at a time.
4. User level threads scheduling done by thread libraries while kernel level done by os.
5. for user level ---> **NO HARDWARE** support required. 
6. for kernel level --->**HARDWARE** support requiered.
7. **user level ---(fast)**
8. **kernel level ---(slow)**


##




