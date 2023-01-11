# Note-for-me
Access Modifier(Public, Private, Protected. Default)
Non-Access(Final, Abstract, Static, ...) 
1. Class
- Default:
+ không hiển thị public phía trước class
+ trong cùng 1 package mới truy cập được 

- Public:
+ Hiển thị chữ public phía trước class
+ Tất cả các class đều có thể truy cập được đến ( kể cả cùng và khác package)

- Final Class:
+ Không cho class khác kế thừa
+ Có thể truy cập khi tạo mới đối tượng
=> Tạo mới đối tượng là gì? 
- Là new đối tượng đó

- Abstract Class:
+ Không cho phép khởi tạo đối tượng 
+ Chỉ cho phép sử dụng thông qua kế thừa
2. Function
- Private:
+ Truy cập bên trong class
+ Không được truy cập bên ngoài Class
+ Không được phép truy cập bởi class kế thừa
