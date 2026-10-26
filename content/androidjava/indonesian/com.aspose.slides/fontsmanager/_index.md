---
title: FontsManager
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mengelola font di seluruh presentasi.
type: docs
url: /id/com.aspose.slides/fontsmanager/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Mengelola font di seluruh presentasi.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Muat presentasi
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Muat font sumber yang akan diganti
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
>      // Simpan presentasi
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substitusi font yang digunakan saat rendering. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substitusi font yang digunakan saat rendering. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Mengembalikan font yang digunakan dalam presentasi |
| [getSubstitutions()](#getSubstitutions--) | Mendapatkan informasi tentang font yang akan diganti pada rendering presentasi. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Mendapatkan informasi tentang font yang akan diganti selama rendering slide yang ditentukan. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Mengembalikan font yang disematkan dalam presentasi |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Menghapus font yang disematkan |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Menambahkan font yang disematkan |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Menambahkan font yang disematkan |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Mengganti font dalam presentasi |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Menentukan tingkat penyematan font dari array byte dan nama font yang diberikan. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Substitusi font yang digunakan saat rendering. Baca/tulis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Mengembalikan:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substitusi font yang digunakan saat rendering. Baca/tulis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Mendapatkan koleksi aturan yang kosong atau telah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // menambahkan aturan ke koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // atau 
>      // inisialisasi instance baru koleksi aturan
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // menambahkan aturan ke koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // dan mengganti koleksi yang ada dengan yang baru di FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Mendapatkan koleksi aturan yang kosong atau telah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // menambahkan aturan ke koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // atau 
>      // inisialisasi instance baru koleksi aturan
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // menambahkan aturan ke koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // dan mengganti koleksi yang ada dengan yang baru di FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Mengembalikan font yang digunakan dalam presentasi

**Mengembalikan:**
com.aspose.slides.IFontData[] - Sebuah array font
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Mendapatkan informasi tentang font yang akan diganti pada rendering presentasi.

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


**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Koleksi semua substitusi font [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Mendapatkan informasi tentang font yang akan diganti selama rendering slide yang ditentukan.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slides | int[] | Sebuah array indeks slide untuk mendapatkan informasi substitusi font, dimulai dari 1. |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sebuah koleksi semua substitusi font ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) untuk slide yang ditentukan.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Mengembalikan font yang disematkan dalam presentasi

**Mengembalikan:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Menghapus font yang disematkan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Menambahkan font yang disematkan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Menambahkan font yang disematkan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Mengganti font dalam presentasi

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font sumber |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font tujuan |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Info substitusi font |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Koleksi aturan substitusi font |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Mengambil semua font yang digunakan dalam presentasi
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Mendapatkan array byte yang mewakili gaya reguler dari font pertama dalam presentasi
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font yang berisi informasi tentang font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Gaya font yang datanya akan diambil [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Mengembalikan:**
byte[] - Sebuah array byte yang berisi data font untuk gaya font yang ditentukan. Jika data font atau gaya tidak ditemukan, mengembalikan null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Menentukan tingkat penyematan font dari array byte dan nama font yang diberikan.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Mengambil semua font yang digunakan dalam presentasi
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Mendapatkan array byte yang mewakili gaya reguler dari font pertama dalam presentasi
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Menentukan tingkat penyematan font
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontBytes | byte[] | Array byte yang berisi data font. |
| fontName | java.lang.String | Nama font. |

**Mengembalikan:**
int - Tingkat penyematan font yang ditentukan.