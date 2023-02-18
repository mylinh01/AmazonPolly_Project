# Xây dựng ứng dụng trên AWS. Tìm hiểu Polly và viết ứng dụng minh họa

## Các nội dung chính
- Tìm hiểu Amazon Polly
- Viết ứng dụng Text to Speech để đọc văn bản, tài liệu và trang web
## Công nghệ sử dụng 
1. Amazon Polly

- Giới thiệu về amazon Polly: Amazon Polly là một dịch vụ chuyển đổi văn bản thành giọng nói trên nền tảng đám mây AWS. Cho phép người dùng tạo các ứng dụng có thể nói chuyện và phát triển những thể loại sản phẩm được trang bị khả năng nói hoàn toàn mới. Người dùng chỉ cần cho đầu vào là văn bản mà họ muốn chuyển đổi thành giọng nói trong Amazon Polly API.
- Là dịch vụ Text-to-Speech (TTS) sử dụng công nghệ deep learning tiên tiến để tổng hợp thành lời nói tự nhiên của con người, với hàng chục giọng nói chân thực theo nhiều ngôn ngữ, người dùng có thể xây dựng ứng dụng có giọng nói hoạt động ở nhiều nước khác nhau.
2. Amazon Web Services
3. HTML, CSS, JavaScript

## Thành viên tham gia Project
- Nguyễn Thị Mỹ Linh - 19133032
- Lê Thị Thanh Phương - 19133046
- Võ Thị Ngọc Thắm - 19133051

## Các bước cài đặt
## Bước 1: Tạo User và nhận được Access Key ID và Secret access key

## Bước 2: Tiến hành cài đặt AWS-SDK vào NodeJs
Đầu tiên ta sẽ tạo một thư mục để install AWS-SDK vào

<img width="347" alt="image" src="https://user-images.githubusercontent.com/94701171/169646129-54371789-0ef4-4d0b-b413-3df7c8314507.png">

Ta dùng lệnh: npm install aws-sdk --save để cài đặt

<img width="491" alt="image" src="https://user-images.githubusercontent.com/94701171/169646176-19784e6c-3b8e-4535-a85d-000595d49ef5.png">

Để sử dụng được các dịch vụ ta cần nhúng các link file.js đã cài đặt ở NodeJS vào chương trình và khai báo Object Translate và Polly của SDK

<img width="556" alt="image" src="https://user-images.githubusercontent.com/94701171/169646242-bae740df-9180-4743-a1a4-38ff482ce706.png">

Chọn khu vực và add Accesskey và Secretkey đã tạo ở bước Users vào AWS-SDK

## Các chức năng 
- Điều chỉnh âm sắc của giọng nói
- Điều chỉnh độ lớn của giọng nói
- Đọc vắn bản thuần túy
![image](https://user-images.githubusercontent.com/91240116/219866053-a252b91d-e82c-4a4b-b421-ab9afe49e741.png)
- Đọc các thẻ SSML 
![image](https://user-images.githubusercontent.com/91240116/219866098-3c7aea60-7b1a-4259-bed4-8b4cf7c5762a.png)
- upload tệp để đọc
![image](https://user-images.githubusercontent.com/91240116/219866107-1c5bc64d-f031-4939-a295-2ff728f1b122.png)






