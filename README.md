Linear Algebra Library: Sqrt() Example
======================================

## 1. OVERVIEW

Implementing the math function sqrt from the Linear Algebra Library 

## 2. SOFTWARE TOOLS AND SYSTEM REQUIREMENTS

Any Vivado HLS release from 2014.1 to 2016.1

## 3. DESIGN FILE HIERARCHY
```
	
	|   README.md
	\---code
			cordic_atan_11bits.h
		        cordic_defines.h
		    	cordic_isqrt.cpp
		    	cordic_sqrt.cpp
		    	float_sqrt.cpp
			test_main.cpp
    			top_magnitude.cpp
	\---code-opt
			cordic_atan_11bits.h
		        cordic_defines.h
		    	cordic_isqrt.cpp
		    	cordic_sqrt.cpp
		    	float_sqrt.cpp
			test_main.cpp
    			top_magnitude.cpp
	\---impl
			top_fdct_csyth.rpt
	\---script
			script.tcl
			
```

## 4. INSTALLATION AND OPERATING INSTRUCTIONS

1. In the Vivado HLS command line window:

```
	vivado_hls script.tcl
```

## 5. OTHER INFORMATION

For more information check here: 
[Full Documentation][]
[Vivado HLS User Guide][]

## 6. SUPPORT

For questions and to get help on this project or your own projects, visit the [Vivado HLS Forums][]. 


REF: https://github.com/Xilinx/HLx_Examples
