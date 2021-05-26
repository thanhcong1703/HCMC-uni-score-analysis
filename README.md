# HCMC-uni-score-analysis
# BÁO CÁO ĐỒ ÁN CUỐI KỲ
CẤU TRÚC ĐỒ ÁN
 raw_data.txt : file html crawl data web 
 unicode.txt: file mã unicode
 process_all: chứa file code cleandata và tạo file csv
 clean_data.csv: chứa data đã làm sạch và xử lý
 README.MD: chứa báo cáo đồ án
# 1. Thành viên nhóm và phân công
Thành viên
Nguyễn Sỹ Thành Công, MSSV: 18520540
Công việc
*Phát biểu bài toán, đặt ra câu hỏi từ đó đặt ra các yêu cầu để thu thập phân tích dữ liệu
*Thu thập dữ liệu 
*Clean data
*Viết báo cáo
*Phân tích và Visualize dữ liêụ
# 2 Thư viện sử dụng
      *numpy
      *matlotlib 
# 3. Tổng quan đồ án
   
Thu thập xử lý làm sạch và phân tích dữ liệu điểm thi đại học của thí sinh tại TPHCM 2020

INPUT: raw_data.txt : file html crawl data web ![image](https://user-images.githubusercontent.com/84485418/118959058-2ad38f80-b98c-11eb-8f8d-a6e2bf431bef.png)
data sau khi đã làm sạch 
OUTPUT: clean_data.csv: chứa data đã làm sạch và xử lý bằng python
![image](https://user-images.githubusercontent.com/84485418/119019887-d6e69c00-b9c7-11eb-929d-6662b240a587.png)

Biểu đồ barchart số học sinh bỏ thi hoặc không đăng ký thi các môn - barchart.py
![image](https://user-images.githubusercontent.com/84485418/119726757-aa38f580-be9b-11eb-8bee-1785f46ae49d.png)
Biểu đồ piechart học sinh thường thi mấy môn - piechart.py
![image](https://user-images.githubusercontent.com/84485418/119726898-d94f6700-be9b-11eb-9452-8cb4b347be1a.png)
Biểu đồ barchart điểm trung bình theo số lượng môn thi – Barchart_average_score.py
![image](https://user-images.githubusercontent.com/84485418/119727155-2b908800-be9c-11eb-9c14-bb937efdaaf6.png)
Điểm trung bình theo nhóm tuổi - Barchart_linechart.py
![image](https://user-images.githubusercontent.com/84485418/119727449-79a58b80-be9c-11eb-923d-62b33c5f0b3c.png)
Biểu đồ barchart những Họ nào phổ biến nhất - lastname_barchart.py
![image](https://user-images.githubusercontent.com/84485418/119727789-eae53e80-be9c-11eb-89a5-82563e49125c.png)
Biểu đồ barchart những tên nào phổ biến nhất
![image](https://user-images.githubusercontent.com/84485418/119727707-d012ca00-be9c-11eb-8471-0cdce4f24d70.png)
Học sinh có tên dài nhất
![image](https://user-images.githubusercontent.com/84485418/119727964-1d8f3700-be9d-11eb-87bc-e80e458de635.png)


