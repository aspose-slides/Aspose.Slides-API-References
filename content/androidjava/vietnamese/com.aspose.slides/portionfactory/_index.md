---
title: PortionFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo các phần kiểm tra
type: docs
url: /vi/com.aspose.slides/portionfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Cho phép tạo các phần kiểm tra

--------------------

Để tương thích COM
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createPortion()](#createPortion--) | Tạo một phần văn bản trống. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Tạo một phần văn bản từ chuỗi được chỉ định. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Tạo một phần bằng cách sử dụng dữ liệu phần đã chỉ định. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

Tạo một phần văn bản trống.

**Trả về:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

Tạo một phần văn bản từ chuỗi được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| str | java.lang.String | String. |

**Trả về:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

Tạo một phần bằng cách sử dụng dữ liệu phần đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Một phần để sử dụng. |

**Trả về:**
[IPortion](../../com.aspose.slides/iportion) - Portion.