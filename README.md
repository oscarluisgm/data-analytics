![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)

# Data Analysis Course (Taken by Oscar Guerra) 

**1)-NumPy Arrays:**  

-**NumPy Arrays:**  

    -Selecting, slicing, forcing to get a NumPy Array OutPut
    b[[0,2,-1]].  
    -Array Types: int64, float64, int8, unicode (U1)  
    -Dimensions and Shapes: .shape, .ndim.  
    -Statistics with Numpy .sum(), mean(), std(), min()  
    -Array Evaluation (Boolean Output) and Array  
    -sys.getsizeof(int, float, str...)  
    -np.dtype(int).itemsize:(64bit default in my OS = **8Bytes**)  
    -np.dtype(np.int8).itemsize:(**1Byte**)  
    -Lists Vs. Arrays: 
       *List Size: sys.getsizeof([1]):64Bytes.  
       *Np Array Size: np.array([1]).itemsize:8Bytes  
       *List Performance: **%time** sum ("x^2 for x in l"):CPU total: **1.45s**  
       *Np Array Performance: **%time** np.sum(G^2): CPU total: **57.8ms**  
       
## Jupyter Notebook (Ubuntu)

1-python3 -m venv ~/py_envs  
2-source ~/py_envs/bin/activate  
3-python3 -m pip install jupyter  
4-jupyter notebook  

## Sys path reference to append lib modules to a .ipynb in jupyter 

import sys  
sys.path.append('/home/user/py_envs/lib/python3.12/site-packages')  

## Virtual Environment
python3 -m venv ~/py_envs  
source ~/py_envs/bin/activate  


[👨‍💼Oscar Guerra's LinkedIn profile](https://ve.linkedin.com/in/oscar-luis-guerra-mata-482914a2)

>This is an Oscar's GitHub repository for Data Analysis with Python








