# TỔNG HỢP VỀ How JavaSript Works Behind the Scenes

Tìm hiểu xem nguyên tắc JavaScript hoạt động như thế nào.

## Tổng quan chuyên sâu về JavaScript

**(An High-Level Overview Of JavaScript)**

---

![What is JavaScript](./images/001-what-is-javascript1.png "What is JavaScript")

> **_`JAVASCRIPT IS A HIGH-LEVEL, PROTOTYPE-BASED OBJECT-ORIENTED, MULTI-PARADIGM, INTERPRETED OR JUST-IN-TIME COMPILED, DYNAMIC, SINGLE-THREADED, GARBAGE-COLLECTED PROGRAMMING LANGUAGE WITH FIRST-CLASS FUNCTIONS AND A NON-BLOCKING EVENT LOOP CONCURRENCY MODEL.`_**

JAVASCRIPT LÀ **_`NGÔN NGỮ CẤP CAO`_**, DỰA TRÊN **_`NGUYÊN MẪU HƯỚNG ĐỐI TƯỢNG`_**, **_`ĐA MÔ HÌNH`_**, ĐƯỢC **_`PHIÊN DỊCH HOẶC BIÊN DỊCH ĐÚNG LÚC`_**, CÓ TÍNH **_`ĐỘNG`_**, CHẠY **_`ĐƠN LUỒNG`_**, NGÔN NGỮ LẬP TRÌNH **_`THU GOM RÁC`_** VỚI NHỮNG **_`CHỨC NĂNG HẠNG NHẤT`_** VÀ **_`MÔ HÌNH ĐỒNG THỜI VÒNG LẶP SỰ KIỆN`_** KHÔNG CHẶN.

![What is JavaScript](./images/002-what-is-javascript2.png "What is JavaScript")

![What is JavaScript](./images/003-what-is-javascript3.png "What is JavaScript")

## CHI TIẾT

---

![What is JavaScript](./images/004-what-is-javascript4.png "What is JavaScript")

### 1. A Hight-Level

Không cần phải xử lý liên quan đến các bộ nhớ để tối ưu chương trình.

- Khi các phần mềm bậc thấp phải khai báo vùng bộ nhớ cần dùng, sau khi sử dụng xong phải clean release hay giải phóng bộ nhớ để tránh bị tràn bộ nhớ.
- Với ngôn ngữ bậc cao thì không cần quan tâm để việc dọn dẹp xử lý bộ nhớ này sau khi thực hiện xong.

![A Hight-Level](./images/005-a-hight-level.png "A Hight-Level")

### 2. Garbage-Collected Programming Language

Việc xử lý những biến tạm, các khai báo không sử dụng nữa sẽ được thực hiện tự động.

- Sử dụng thuật toán bên bên trong công cụ của JavaScript.
- Tự động loại bỏ các đối tượng cũ, không sử dụng khỏi bộ nhớ máy tính để khỏi làm nghẽn hay quá tải.
- Làm sạch bộ nhớ theo thời gian và không cần phải thực hiện thao tác này theo cách thủ công.

![Garbage-Collected Programming Language](./images/06-clean-memory.png "Garbage-Collected Programming Language")

### 3. Interpreted or Just-In-Time Compiled

Được phiên dịch hoặc biên dịch cùng lúc.

- Khi viết ngôn ngữ các lập trình viên thường viết bằng ngôn ngữ **_`(Human Code)`_** có thể đọc được dể dàng, nhưng để cho máy tính hiểu thì các ngôn ngữ cần phải được biên dịch qua ngôn ngữ của máy **_`(Machine Code)`_** với các ký tự 0 và 1 để máy có thể thực hiện.
- Việc biên dịch này được thực hiện ngay trong ngôn ngữ JavaScript khi thực hiện.

![Compiled to Machine Code](./images/06-compiled01.png "Compiled to Machine Code")

### 4. Multi-Paradigm

Ngôn ngữ lập trình Đa mô hình.

![Multi-Paradigm](./images/07-multi-paradigm.png "Multi-Paradigm")

> **Paradigm** : **_Mô hình_** là một cách tiếp cận và tư duy tổng thể về cấu trúc mã, nó sẽ định hướng trực tiếp đến phong cách viết mã và các kỹ thuật viết mã code của bạn trong một dự án sử dụng một mô hình nhất định.

![Three Paradigm](./images/08-3-paradigm.png "Three Paradigm")

Các mô hình lập trình là:

1. Procedural programming(PP) : Lập trình theo hướng thủ tục trình tự
2. Obeject-oriented programming(OOP)
3. Function programming(FP)

Xem thêm ở [`Functional Programming và Procedural Programming`](./plus20.FP_PP.md).
