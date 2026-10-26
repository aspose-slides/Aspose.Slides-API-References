---
title: IOverrideTheme
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một chủ đề ghi đè.
type: docs
url: /vi/com.aspose.slides/ioverridetheme/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Biểu diễn một chủ đề ghi đè.
## Phương thức

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | Giá trị true có nghĩa là ColorScheme, FontScheme, FormatScheme là null và bất kỳ việc ghi đè nào với đối tượng theme này đều bị vô hiệu hoá. |
| [initColorScheme()](#initColorScheme--) | Khởi tạo ColorScheme bằng đối tượng mới để ghi đè ColorScheme của InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Khởi tạo ColorScheme bằng đối tượng mới để ghi đè ColorScheme của InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Khởi tạo ColorScheme bằng đối tượng mới để ghi đè ColorScheme của InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Khởi tạo FontScheme bằng đối tượng mới để ghi đè FontScheme của InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Khởi tạo FontScheme bằng đối tượng mới để ghi đè FontScheme của InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Khởi tạo FontScheme bằng đối tượng mới để ghi đè FontScheme của InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Khởi tạo FormatScheme bằng đối tượng mới để ghi đè FormatScheme của InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Khởi tạo FormatScheme bằng đối tượng mới để ghi đè FormatScheme của InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Khởi tạo FormatScheme bằng đối tượng mới để ghi đè FormatScheme của InheritedTheme. |
| [clear()](#clear--) | Đặt ColorScheme, FontScheme, FormatScheme thành null để vô hiệu hoá bất kỳ việc ghi đè nào với đối tượng theme này. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Giá trị true có nghĩa là ColorScheme, FontScheme, FormatScheme là null và bất kỳ việc ghi đè nào với đối tượng theme này đều bị vô hiệu hoá. Boolean chỉ đọc.

**Trả về:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Khởi tạo ColorScheme bằng đối tượng mới để ghi đè ColorScheme của InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Khởi tạo ColorScheme bằng đối tượng mới để ghi đè ColorScheme của InheritedTheme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Dữ liệu để khởi tạo từ. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Khởi tạo ColorScheme bằng đối tượng mới để ghi đè ColorScheme của InheritedTheme và khởi tạo dữ liệu của đối tượng mới này bằng dữ liệu của ColorScheme của InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Khởi tạo FontScheme bằng đối tượng mới để ghi đè FontScheme của InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Khởi tạo FontScheme bằng đối tượng mới để ghi đè FontScheme của InheritedTheme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Dữ liệu để khởi tạo từ. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Khởi tạo FontScheme bằng đối tượng mới để ghi đè FontScheme của InheritedTheme và khởi tạo dữ liệu của đối tượng mới này bằng dữ liệu của FontScheme của InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Khởi tạo FormatScheme bằng đối tượng mới để ghi đè FormatScheme của InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Khởi tạo FormatScheme bằng đối tượng mới để ghi đè FormatScheme của InheritedTheme.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Dữ liệu để khởi tạo từ. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Khởi tạo FormatScheme bằng đối tượng mới để ghi đè FormatScheme của InheritedTheme và khởi tạo dữ liệu của đối tượng mới này bằng dữ liệu của FormatScheme của InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Đặt ColorScheme, FontScheme, FormatScheme thành null để vô hiệu hoá bất kỳ việc ghi đè nào với đối tượng theme này.