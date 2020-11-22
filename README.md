<h1 align="center">Time Domain Features</h1>



<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="https://github.com/shareqahmed" target="_blank">Author</a>
</p>

<br>

## :dart: Time Domain Running Window Statistical Features  ##
This notebook implements useful statistical functions on rolling/moving/sliding windows, including Mean, RMS, Variance, Skewness, Kurtosis and Standard Deviation. Both fixed-length and variable-length window iteration can be changed in the function. Suppose we have a function `running_kur(window, vector)` we can set any number for `window` and the input or output data for `vector`. The functions are mapped in a dictionary `function_order`as:
| Operation        | Key     | Value          | Comments |
| ---------------- |:-------:|:--------------:|-----------------------------|
| Mean             | r_m     | running_mean   | Arithmetic mean of window values |
| RMS              | r_rms   | running_rms    | Set of most common values, tracked using a bi-directional counter |
| Var              | r_var   | running_var    | Variance, uses Welford's algorithm for better numerical stability |
| Std              | r_std   | running_std    | Standard deviation, uses Welford's algorithm |
| Skew             | r_skew  | running_skew   | Skewness of the window |
| Kurtosis         | r_kur   | running_kur    | Kurtosis of the window |


## :sparkles: Data  ##
The type of input and output variables can be changed. 
The data had 5 Input types as:
:heavy_check_mark: INPUT_01;\
:heavy_check_mark: INPUT_02;\
:heavy_check_mark: INPUT_03;\
:heavy_check_mark: INPUT_04;\
:heavy_check_mark: INPUT_05;\

The data has 3 types of Output sensors:
:heavy_check_mark: a_sensor: quantity=5;\
:heavy_check_mark: b_sensor: quantity=2;\
:heavy_check_mark: c_sensor: quantity=1;\

## :rocket: Technologies ##

The following tools were used in this project:

- [Python](https://www.python.org/)


## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Python](https://www.python.org/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/shareqahmed/time_domain_features

# Access
$ cd time_domain_features

```

Made with :heart: by <a href="https://github.com/shareqahmed" target="_blank">shareqahmed</a>

&#xa0;

<a href="#top">Back to top</a>
