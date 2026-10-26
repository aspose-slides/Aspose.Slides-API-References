---
title: Storage
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một bộ lưu trữ dữ liệu tạm thời cho .
type: docs
url: /vi/com.aspose.slides/storage/
---
**Kế thừa:**
java.lang.Object
```
public final class Storage
```

Biểu diễn một bộ lưu trữ dữ liệu tạm thời cho [WebDocument](../../com.aspose.slides/webdocument).
## Các hàm khởi tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Storage()](#Storage--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Đưa giá trị vào bộ lưu trữ. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Lấy dữ liệu từ bộ lưu trữ. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Xác định xem bộ lưu trữ có chứa phần tử với khóa đã chỉ định hay không. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Đưa giá trị vào bộ lưu trữ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| key | java.lang.String | Khóa cho giá trị. |
| value | TValue | Giá trị. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Lấy dữ liệu từ bộ lưu trữ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| key | java.lang.String | Khóa của giá trị. |

**Trả về:**
TValue - Giá trị dữ liệu nếu nó có trong bộ sưu tập dữ liệu, null trong các trường hợp còn lại.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Xác định xem bộ lưu trữ có chứa phần tử với khóa đã chỉ định hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| key | java.lang.String | Khóa của giá trị. |

**Trả về:**
boolean - Đúng nếu bộ lưu trữ chứa phần tử với khóa đã chỉ định, sai trong các trường hợp còn lại.