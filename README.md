# Bài toán bao phủ sử dụng nhiều UAV
Bài toán được lập ra trên phương diện sử dụng nhiều bầy đàn UAV để thực hiện thuật toán bao phủ một khu vực. Các UAV sẽ bay theo hình chữ V để giám sát thu thập ảnh tại một khu vực được lựa chọn.

Bài toán nghiên cứu được thực hiện dưới dự án QG.21.26: *"Re- silience for Preserving Multi-Robot Network in Dynamic Environment"* của Vietnam National University, Hanoi. Và được công bố trong hội nghị International Conference on Control, Automation and Information Sciences ([ICCAIS 2022](http://iccais2022.org/)). Bài báo được tìm thấy ở đây [here](https://ieeexplore.ieee.org/document/9990236).

## Phầm mềm lập trình: Visual Studio, Matlab.
## Ngôn ngữ sử dụng: Python, Matlab.
## Kết quả thu được:
So sánh dựa theo 3 thuật toán để chứng minh sự hiệu quả của phương pháp dựa trên 3 thuật toán mẫu: Thuật toán chia lưới, thuật toán đường đi ngẫu nhiên và thuật toán đường đi tối ưu.

## Statistical simulation results of the multi-UAV coverage strategy
The obtained to evaluate the performance of the proposed multi-UAV coverage strategy for the V-shaped formation.

The resulting simulation uses 20 different maps and robot numbers and 3 different algorithms for evaluation.

Matlab software is used to analyze the images after simulation and make comparisons based on the statistics.
## Maps
The generated maps are used as inputs to this simulation [here](https://github.com/ndamtruong2k/Statistical-simulation-results-of-the-multi-UAV-coverage-strategy/tree/main/Map).
## The Results
After simulating Op-RCPP, [here](https://github.com/ndamtruong2k/Statistical-simulation-results-of-the-multi-UAV-coverage-strategy/tree/main/Op) are the results.

After simulating nonOp-RCPP, [here](https://github.com/ndamtruong2k/Statistical-simulation-results-of-the-multi-UAV-coverage-strategy/tree/main/Bad) are the results.

After simulating Grid-based, [here](https://github.com/ndamtruong2k/Statistical-simulation-results-of-the-multi-UAV-coverage-strategy/tree/main/Grid) are the results.
## The statistics
Statistical simulation results of the multi-UAV coverage strategy using V-shaped formation with 3, 5, 7 UAVs, and different coverage paths.
### Sweep coverage rate 
![coverage_rate](https://github.com/ndamtruong2k/Statistical-simulation-results-of-the-multi-UAV-coverage-strategy/blob/main/CoveragePer.pdf)
### Fight time 
![fight_time](https://github.com/ndamtruong2k/Statistical-simulation-results-of-the-multi-UAV-coverage-strategy/blob/main/CoverageTime.pdf)

