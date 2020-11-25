# Hbird E203 + RT-Thread on Lichee Tang (EG4S20)

## Step 1 - Upload FPGA bitstream



## Step 2 - Build and compile rt-thread firmware

```
$ cd hbird-sdk/application/rtthread/msh/
$ export NUCLEI_TOOL_ROOT=/opt/nuclei/             # replace with your path
$ export PATH=$NUCLEI_TOOL_ROOT/gcc/bin:$NUCLEI_TOOL_ROOT/openocd/bin:$PATH
$ make SOC=hbird BOARD=hbird_eval CORE=e203 upload
```
