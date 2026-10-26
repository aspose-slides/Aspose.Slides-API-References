---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /vi/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Quản lý phông chữ trên toàn bộ bản trình chiếu.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Thay thế phông chữ để sử dụng khi kết xuất Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Thay thế phông chữ để sử dụng khi kết xuất Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế chính xác bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế chính xác bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Trả về các phông chữ được sử dụng trong bản trình chiếu |
| [getSubstitutions()](#getSubstitutions--) | Lấy thông tin về các phông chữ sẽ được thay thế khi kết xuất bản trình chiếu. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình kết xuất các slide đã chỉ định. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Trả về các phông chữ được nhúng trong bản trình chiếu |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Xóa phông chữ đã nhúng |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Thêm phông chữ đã nhúng. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Thêm phông chữ đã nhúng |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Thay thế phông chữ trong bản trình chiếu |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Thay thế phông chữ trong bản trình chiếu bằng thông tin được cung cấp trong [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Thay thế phông chữ trong bản trình chiếu bằng thông tin được cung cấp trong bộ sưu tập [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lấy mảng byte biểu diễn dữ liệu phông chữ cho kiểu phông chữ và dữ liệu phông chữ đã chỉ định. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Xác định mức độ nhúng của phông chữ từ mảng byte và tên phông chữ đã cho. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Thay thế phông chữ để sử dụng khi kết xuất Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Trả về:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Thay thế phông chữ để sử dụng khi kết xuất Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế chính xác bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // thêm quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // khởi tạo một thể hiện mới của bộ sưu tập quy tắc
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // thêm quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // và thay thế bộ sưu tập hiện có bằng bộ mới trong FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế chính xác bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // thêm quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // hoặc 
>      // khởi tạo một thể hiện mới của bộ sưu tập quy tắc
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // thêm quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // và thay thế bộ sưu tập hiện có bằng bộ mới trong FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Trả về các phông chữ được sử dụng trong bản trình chiếu

**Trả về:**
com.aspose.slides.IFontData[] - Một mảng các phông chữ

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Lấy thông tin về các phông chữ sẽ được thay thế khi kết xuất bản trình chiếu.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Bộ sưu tập tất cả các thay thế phông chữ [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình kết xuất các slide đã chỉ định.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slides | int[] | Mảng các chỉ số slide để lấy thông tin thay thế phông chữ, bắt đầu từ 1. |

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Bộ sưu tập tất cả các thay thế phông chữ ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) cho các slide đã chỉ định.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Trả về các phông chữ đã nhúng trong bản trình chiếu

**Trả về:**
com.aspose.slides.IFontData[] - Phông chữ đã nhúng IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Xóa phông chữ đã nhúng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Đối tượng dữ liệu phông chữ [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Thêm phông chữ đã nhúng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Đối tượng dữ liệu phông chữ [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Quy tắc nhúng phông chữ [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Lưu ý khi sao chép bất kỳ phông chữ nào, hầu hết phông chữ đều có bản quyền. Trước tiên hãy xác định giấy phép của phông chữ và kiểm tra chúng có thể được chuyển sang máy khác một cách tự do hay không. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Thêm phông chữ đã nhúng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | byte[] | Dữ liệu phông chữ  byte[]  |
| embedFontRule | int | Quy tắc nhúng phông chữ [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Lưu ý khi thêm bất kỳ phông chữ nào, hầu hết phông chữ đều có bản quyền. Trước tiên hãy xác định giấy phép của phông chữ và kiểm tra chúng có thể được chuyển sang máy khác một cách tự do hay không. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Thay thế phông chữ trong bản trình chiếu

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ nguồn |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ đích |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Thay thế phông chữ trong bản trình chiếu bằng thông tin được cung cấp trong [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Thông tin thay thế phông chữ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Thay thế phông chữ trong bản trình chiếu bằng thông tin được cung cấp trong bộ sưu tập [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Bộ sưu tập thông tin thay thế phông chữ |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Lấy mảng byte biểu diễn dữ liệu phông chữ cho một kiểu phông chữ và dữ liệu phông chữ đã chỉ định.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Lấy tất cả các phông chữ được sử dụng trong bản trình chiếu
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Lấy mảng byte đại diện cho kiểu Regular của phông chữ đầu tiên trong bản trình chiếu
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Đối tượng dữ liệu phông chữ chứa thông tin về phông chữ [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Kiểu phông chữ mà dữ liệu cần được lấy [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Trả về:**
byte[] - Một mảng byte chứa dữ liệu phông chữ cho kiểu phông chữ đã chỉ định. Nếu dữ liệu phông chữ hoặc kiểu không tồn tại, trả về null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Xác định mức độ nhúng của phông chữ từ mảng byte và tên phông chữ đã cho.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Lấy tất cả các phông chữ được sử dụng trong bản trình chiếu
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Lấy mảng byte đại diện cho kiểu Regular của phông chữ đầu tiên trong bản trình chiếu
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Xác định mức độ nhúng của phông chữ
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontBytes | byte[] | Mảng byte chứa dữ liệu phông chữ. |
| fontName | java.lang.String | Tên của phông chữ. |

**Trả về:**
int - Mức độ nhúng của phông chữ đã chỉ định.