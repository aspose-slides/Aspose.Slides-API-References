---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /vi/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Cho phép tạo các phần kiểm tra

--------------------

Đối với khả năng tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createPortion()](#createPortion--) | Tạo một phần văn bản trống. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Tạo một phần văn bản từ chuỗi được chỉ định. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Tạo một phần bằng cách sử dụng dữ liệu phần được chỉ định. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Tạo một phần văn bản trống.

**Trả về:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
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
public abstract IPortion createPortion(IPortion portion)
```


Tạo một phần bằng cách sử dụng dữ liệu phần được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Một phần để sử dụng. |

**Trả về:**
[IPortion](../../com.aspose.slides/iportion) - Portion.