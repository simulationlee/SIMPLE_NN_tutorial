## SIMPLE_NN Tutorial
### Environment
------------
- Python ``3.9``
- PyTorch ``1.10.1``
- LAMMPS ``29Aug2024``
- numpy ``1.22``

### Installation issues
------------
1. copy path typo (' - ' -> ' _ ')
   
reference code


    cp SIMPLE-NN_v2/simple-nn/features/symmetry_function/pair_nn* /path/to/lammps/src/
    cp SIMPLE-NN_v2/simple-nn/features/symmetry_function/symmetry_function.h /path/to/lammps/src/


after revision


    cp <PATH./simple_nn/features/symmetry_function/pair_nn* <PATH>/lammps/src/
    cp <PATH>/simple_nn/features/symmetry_function/symmetry_function.h <PATH>/lammps/src/


2. Run setup.py  
check #115. (recommend setting up the SIMPLE_NN repository within a Conda virtual environment.)  

4. SIMPLE-NN test fail

editing..
