Region Growing

Hàm chỉ có thể sử dụng được với ảnh xám
Để sử dụng được hàm này cần phải chuẩn hóa ảnh bằng hàm im2double ảnh xám được thêm vào
Ví dụ: I=im2double(imread('test.jpg')

Gọi hàm: Region_Growing(J,x,y,reg_maxdist)
Trong đó:
x,y là tọa độ của Seed Point, nếu muốn tự chọn bằng tay thì nhập x=y=0
reg_maxdist là khoảng chênh lệch lớn nhất của các pixel trong vùng so với Seed Point (0<=reg_maxdist<=1)
Nếu không nhập reg_maxdist thì mặc định là 0.2
