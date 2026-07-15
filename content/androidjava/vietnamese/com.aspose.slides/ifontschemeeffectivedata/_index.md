---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Đối tượng bất biến chứa các thuộc tính của giao thức phông chữ hiệu quả.
type: docs
url: /vi/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Đối tượng bất biến chứa các thuộc tính của giao thức phông chữ hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getMinor()](#getMinor--) | Trả về bộ sưu tập phông chữ cho phần "body" của slide. |
| [getMajor()](#getMajor--) | Trả về bộ sưu tập phông chữ cho phần "heading" của slide. |
| [getName()](#getName--) | Trả về tên của font scheme. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Trả về bộ sưu tập phông chữ cho phần "body" của slide. Chỉ đọc [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Trả về:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Trả về bộ sưu tập phông chữ cho phần "heading" của slide. Chỉ đọc [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Trả về:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Trả về tên của font scheme. Chỉ đọc String.

**Trả về:**
java.lang.String