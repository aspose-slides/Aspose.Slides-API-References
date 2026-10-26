---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Đối tượng bất biến chứa các thuộc tính của lược đồ phông chữ hiệu quả.
type: docs
url: /vi/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Đối tượng bất biến chứa các thuộc tính của lược đồ phông chữ hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getMinor()](#getMinor--) | Trả về tập hợp phông chữ cho phần "body" của slide. |
| [getMajor()](#getMajor--) | Trả về tập hợp phông chữ cho phần "heading" của slide. |
| [getName()](#getName--) | Trả về tên lược đồ phông chữ. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Trả về tập hợp phông chữ cho phần "body" của slide. Chỉ đọc [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Trả về:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Trả về tập hợp phông chữ cho phần "heading" của slide. Chỉ đọc [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Trả về:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Trả về tên lược đồ phông chữ. Chỉ đọc String.

**Trả về:**
java.lang.String