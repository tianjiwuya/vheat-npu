# vheat-npu
在npu上实现vheat

```source /usr/local/Ascend/ascend-toolkit/set_env.sh```

Installation

Step 1: Clone the vHeat repository:

To get started, first clone the vHaet repository and navigate to the project directory:

``` git clone https://github.com/MzeroMiko/vHeat.git``` 
 
 ``` cd vHeat``` 

 Step 2: Environment Setup:

Create and activate a new conda environment

``` conda create -n vHeat``` 

``` conda activate vHeat``` 

Install Dependencies

```conda install -c conda-forge rust```

验证

```rustc --version```

```cargo --version```

如果能成功输出版本信息，则说明已经装好了 Rust 工具链

```pip install -r requirements.txt```

