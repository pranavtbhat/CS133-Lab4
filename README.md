# CS133-Lab4
AWS helper repository for Lab4 (CS133)

# Instructions
Once you ssh into your instance:
- git clone https://github.com/pranavtbhat/CS133-Lab4.git
- cd CS133-Lab4
- source install.sh (This step may take about 10 minutes)

# Running the OpenCL example
- cd release/example
- source ../setup_oclgpu.sh
- make clean && make && ./vecadd_gpu
