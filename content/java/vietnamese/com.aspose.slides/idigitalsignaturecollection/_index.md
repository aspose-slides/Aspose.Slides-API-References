---
title: IDigitalSignatureCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các chữ ký số được đính kèm vào tài liệu.
type: docs
url: /vi/com.aspose.slides/idigitalsignaturecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Represents a collection of digital signatures attached to a document.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về chữ ký theo chỉ mục. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Thêm chữ ký vào cuối bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa chữ ký tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các chữ ký khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Trả về chữ ký theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Thêm chữ ký vào cuối bộ sưu tập.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Chữ ký cần thêm. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa chữ ký tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của chữ ký cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các chữ ký khỏi bộ sưu tập.