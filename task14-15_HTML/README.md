#Mục lục

[1.HTML là gì?](#1)
[2.HTML được xử lý như thế nào?](#2)
[3.Vai trò của HTML](#3)
[4.Cấu trúc của HTML](#4)

<a name="1"></a>

#1.HTML là gì?

HTML là chữ viết tắt của cụm từ `HyperText Markup Language` (ngôn ngữ đánh dấu siêu văn bản), được sử dụng để tạo một trang web, trên một website có thể sẽ chứa nhiều trang và mỗi trang được quy ra là một tài liệu HTML (thi thoảng mình sẽ ghi là một tập tin HTML). Cha đẻ của HTML là **Tim Berners-Lee**, cũng là người khai sinh ra **World Wide Web** và chủ tịch của **World Wide Web Consortium** (W3C – tổ chức thiết lập ra các chuẩn trên môi trường Internet).

<a name="2"></a>

#2.HTML được xử lý như thế nào?

Khi một tập tin `HTML` được hình thành, việc xử lý nó sẽ do trình duyệt web đảm nhận. Trình duyệt sẽ đóng vai trò đọc hiểu nội dung HTML từ các thẻ bên trong và sẽ chuyển sang dạng văn bản đã được đánh dấu để đọc, nghe hoặc hiểu (do các bot máy tính hiểu).

<a name="3"></a>

#3.Vai trò của HTML

- **Website tĩnh** (static web) – Là một website không giao tiếp với máy chủ web để gửi nhận dữ liệu mà chỉ có các dữ liệu được khai báo sẵn bằng `HTML` và trình duyệt đọc.
- **Website động** (dynamic web) – Là một website sẽ giao tiếp với một máy chủ để gửi nhận dữ liệu, các dữ liệu đó sẽ gửi ra ngoài cho người dùng bằng văn bản `HTML` và trình duyệt sẽ hiển thị nó. Để một website có thể giao tiếp với máy chủ web thì sẽ dùng một số ngôn ngữ lập trình dạng **server-side** như **PHP, ASP.NET, Ruby,..**để thực hiện. Ví dụ như một website làm bằng *WordPress* là website động.

<a name="4"></a>

#4.Cấu trúc của HTML

Như mình đã nói ở trên, HTML sẽ được khai báo bằng các phần tử bởi các từ khóa. Nội dung nằm bên trong cặp từ khóa sẽ là nội dung bạn cần định dạng với `HTML`

Cấu trúc của 1 file `HTML`

    <!DOCTYPE html>
    <html>
    <head>
    <title>Page Title</title>
    </head>
    <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
    </body>
    </html>


Ví dụ 
    
    <p> Sầu sô ciu đẹp trai nhất thế gian</p>
    <b> Học HTML </b>

Kết quả sẽ là:

Sầu sô ciu đẹp trai nhất thế gian
**Học HTMl**







