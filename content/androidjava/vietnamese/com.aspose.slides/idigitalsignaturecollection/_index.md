---
title: IDigitalSignatureCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các chữ ký số được đính kèm vào tài liệu.
type: docs
url: /vi/com.aspose.slides/idigitalsignaturecollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Biểu diễn một tập hợp các chữ ký số được đính kèm vào tài liệu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về chữ ký theo chỉ mục. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Thêm chữ ký vào cuối tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa chữ ký tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả chữ ký khỏi tập hợp. |
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


Thêm chữ ký vào cuối tập hợp.

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
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Chữ ký để thêm. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa chữ ký tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của chữ ký cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả chữ ký khỏi tập hợp.