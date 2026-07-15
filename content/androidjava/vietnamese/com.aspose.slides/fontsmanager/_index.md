---
title: FontsManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Quản lý phông chữ trong toàn bộ bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/fontsmanager/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Quản lý phông chữ trong toàn bộ bài thuyết trình.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Tải bản trình chiếu
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Tải phông chữ nguồn để thay thế
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Lưu bản trình chiếu
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Các phép thay thế phông chữ được sử dụng khi hiển thị. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Các phép thay thế phông chữ được sử dụng khi hiển thị. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Trả về các phông chữ được sử dụng trong bài thuyết trình |
| [getSubstitutions()](#getSubstitutions--) | Lấy thông tin về các phông chữ sẽ được thay thế khi hiển thị bài thuyết trình. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình hiển thị các slide đã chỉ định. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Trả về các phông chữ được nhúng trong bài thuyết trình |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Xóa phông chữ đã nhúng |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Thêm phông chữ đã nhúng |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Thêm phông chữ đã nhúng |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Thay thế phông chữ trong bài thuyết trình |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Thay thế phông chữ trong bài thuyết trình bằng thông tin được cung cấp trong [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Thay thế phông chữ trong bài thuyết trình bằng thông tin được cung cấp trong bộ sưu tập [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lấy mảng byte đại diện cho dữ liệu phông chữ cho một kiểu phông chữ và dữ liệu phông chữ cụ thể. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Xác định mức độ nhúng của một phông chữ từ mảng byte và tên phông chữ đã cho. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Các phép thay thế phông chữ được sử dụng khi hiển thị. Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Giá trị trả về:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Các phép thay thế phông chữ được sử dụng khi hiển thị. Đọc/ghi [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lấy bộ sưu tập quy tắc trống hoặc đã khởi tạo trước từ FontsManager
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


**Giá trị trả về:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Biểu diễn bộ sưu tập các quy tắc FontFallBack của người dùng để quản lý các bộ sưu tập phông chữ cho việc thay thế thích hợp bằng chức năng fallback Đọc/ghi [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lấy bộ sưu tập quy tắc trống hoặc đã khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Thêm quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // hoặc 
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
public final IFontData[] getFonts()
```

Trả về các phông chữ được sử dụng trong bài thuyết trình

**Giá trị trả về:**
com.aspose.slides.IFontData[] - Một mảng các phông chữ

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Lấy thông tin về các phông chữ sẽ được thay thế khi hiển thị bài thuyết trình.

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

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Bộ sưu tập của tất cả các phép thay thế phông chữ [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Lấy thông tin về các phông chữ sẽ được thay thế trong quá trình hiển thị các slide đã chỉ định.

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
| slides | int[] | Một mảng các chỉ mục slide mà cần lấy thông tin thay thế phông chữ, bắt đầu từ 1. |

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Một bộ sưu tập của tất cả các phép thay thế phông chữ ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) cho các slide đã chỉ định.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Trả về các phông chữ được nhúng trong bài thuyết trình

**Giá trị trả về:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Xóa phông chữ đã nhúng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Thêm phông chữ đã nhúng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Thêm phông chữ đã nhúng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Thay thế phông chữ trong bài thuyết trình

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ nguồn |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ đích |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Thay thế phông chữ trong bài thuyết trình bằng thông tin được cung cấp trong [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Thông tin thay thế phông chữ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Thay thế phông chữ trong bài thuyết trình bằng thông tin được cung cấp trong bộ sưu tập [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Bộ sưu tập các quy tắc thay thế phông chữ |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Lấy mảng byte đại diện cho dữ liệu phông chữ cho một kiểu phông chữ và dữ liệu phông chữ cụ thể.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Lấy tất cả các phông chữ được sử dụng trong bản trình chiếu
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Lấy mảng byte đại diện cho kiểu thường của phông chữ đầu tiên trong bản trình chiếu
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

**Giá trị trả về:**
byte[] - Một mảng byte chứa dữ liệu phông chữ cho kiểu phông chữ đã chỉ định. Nếu không tìm thấy dữ liệu hoặc kiểu phông chữ, trả về null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Xác định mức độ nhúng của một phông chữ từ mảng byte và tên phông chữ đã cho.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Lấy tất cả các phông chữ được sử dụng trong bản trình chiếu
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Lấy mảng byte đại diện cho kiểu thường của phông chữ đầu tiên trong bản trình chiếu
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
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

**Giá trị trả về:**
int - Mức độ nhúng của phông chữ đã chỉ định.