---  
title: IFontsManager  
second_title: Aspose.Slides for Java API Reference  
description: Manages fonts across the presentation.  
type: docs  
url: /vi/com.aspose.slides/ifontsmanager/  
---```
public interface IFontsManager
```

Quản lý phông chữ trên toàn bộ bản trình bày.  
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Thay thế phông chữ để sử dụng khi hiển thị Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Thay thế phông chữ để sử dụng khi hiển thị Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Đại diện cho bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ nhằm thực hiện việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Đại diện cho bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ nhằm thực hiện việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Trả về các phông chữ được sử dụng trong bản trình bày |
| [getSubstitutions()](#getSubstitutions--) | Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình hiển thị bản trình bày |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình hiển thị các slide được chỉ định. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Trả về các phông chữ được nhúng trong bản trình bày |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Xóa phông chữ đã nhúng |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Thêm phông chữ đã nhúng. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Thêm phông chữ đã nhúng |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Thay thế phông chữ trong bản trình bày |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Thay thế phông chữ trong bản trình bày bằng thông tin được cung cấp trong [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Thay thế phông chữ trong bản trình bày bằng thông tin được cung cấp trong bộ sưu tập của [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lấy mảng byte đại diện cho dữ liệu phông chữ cho một kiểu phông chữ và dữ liệu phông chữ được chỉ định. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Xác định mức độ nhúng của phông chữ từ mảng byte và tên phông chữ đã cho. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Thay thế phông chữ để sử dụng khi hiển thị Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Trả về:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Thay thế phông chữ để sử dụng khi hiển thị Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Đại diện cho bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ nhằm thực hiện việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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


**Trả về:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Đại diện cho bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ nhằm thực hiện việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Thêm quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // Hoặc 
>      // Khởi tạo một thể hiện mới của bộ sưu tập quy tắc
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Thêm quy tắc vào bộ sưu tập
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

Trả về các phông chữ được sử dụng trong bản trình bày

**Trả về:**
com.aspose.slides.IFontData[] - Một mảng các phông chữ

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình hiển thị bản trình bày.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Bộ sưu tập của tất cả các thay thế phông chữ [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình hiển thị các slide được chỉ định.

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
| slides | int[] | Một mảng các chỉ số slide để lấy thông tin thay thế phông chữ, bắt đầu từ 1. |

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Một bộ sưu tập của tất cả các thay thế phông chữ ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) cho các slide đã chỉ định.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Trả về các phông chữ được nhúng trong bản trình bày

**Trả về:**
com.aspose.slides.IFontData[] - Phông chữ được nhúng IFontData[]

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
| embedFontRule | int | Quy tắc phông chữ nhúng [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Hãy nhớ khi sao chép bất kỳ phông chữ nào, hầu hết phông chữ đều có bản quyền. Đầu tiên, xác định giấy phép của phông chữ trước và kiểm tra xem chúng có thể được chuyển giao tự do sang máy khác không. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Thêm phông chữ đã nhúng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | byte[] | Dữ liệu phông chữ  byte[] |
| embedFontRule | int | Quy tắc phông chữ nhúng [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Hãy nhớ khi thêm bất kỳ phông chữ nào, hầu hết phông chữ đều có bản quyền. Đầu tiên, xác định giấy phép của phông chữ trước và kiểm tra xem chúng có thể được chuyển giao tự do sang máy khác không. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Thay thế phông chữ trong bản trình bày

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ nguồn |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ đích |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Thay thế phông chữ trong bản trình bày bằng thông tin được cung cấp trong [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Thông tin thay thế phông chữ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Thay thế phông chữ trong bản trình bày bằng thông tin được cung cấp trong bộ sưu tập của [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Bộ sưu tập thông tin thay thế phông chữ |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Lấy mảng byte đại diện cho dữ liệu phông chữ cho một kiểu phông chữ và dữ liệu phông chữ được chỉ định.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Lấy tất cả các phông chữ được sử dụng trong bản trình bày
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Lấy mảng byte đại diện cho kiểu Regular của phông chữ đầu tiên trong bản trình bày
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
byte[] - Một mảng byte chứa dữ liệu phông chữ cho kiểu phông chữ đã chỉ định. Nếu không tìm thấy dữ liệu phông hoặc kiểu, trả về null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Xác định mức độ nhúng của phông chữ từ mảng byte và tên phông chữ đã cho.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Lấy tất cả các phông chữ được sử dụng trong bản trình bày
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Lấy mảng byte đại diện cho kiểu Regular của phông chữ đầu tiên trong bản trình bày
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