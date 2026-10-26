---
title: Storage
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một kho lưu trữ dữ liệu tạm thời cho .
type: docs
url: /vi/com.aspose.slides/storage/
---
**Kế thừa:**
java.lang.Object
```
public final class Storage
```

Đại diện cho một kho lưu trữ dữ liệu tạm thời cho [WebDocument](../../com.aspose.slides/webdocument).
## Khởi tạo

| Constructor | Description |
| --- | --- |
| [Storage()](#Storage--) |  |
## Phương thức

| Method | Description |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Đưa giá trị vào kho lưu trữ. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Lấy dữ liệu từ kho lưu trữ. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Xác định xem kho lưu trữ có chứa phần tử với khóa được chỉ định hay không. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

Đưa giá trị vào kho lưu trữ.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Khóa cho giá trị. |
| value | TValue | Giá trị. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

Lấy dữ liệu từ kho lưu trữ.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Khóa của giá trị. |

**Trả về:**
TValue - Giá trị dữ liệu nếu nó có trong bộ sưu tập dữ liệu, null otherwise.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

Xác định xem kho lưu trữ có chứa phần tử với khóa được chỉ định hay không.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Khóa của giá trị. |

**Trả về:**
boolean - True nếu kho lưu trữ chứa phần tử với khóa được chỉ định, false otherwise.