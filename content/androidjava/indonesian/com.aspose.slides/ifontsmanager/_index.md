---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Mengelola font di seluruh presentasi.
type: docs
url: /id/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Mengelola font di seluruh presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substitusi font yang digunakan saat merender Baca/tulis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substitusi font yang digunakan saat merender Baca/tulis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Mewakili koleksi pengguna dari aturan FontFallBack untuk mengelola koleksi font untuk substitusi yang tepat melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Mewakili koleksi pengguna dari aturan FontFallBack untuk mengelola koleksi font untuk substitusi yang tepat melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Mengembalikan font yang digunakan dalam presentasi |
| [getSubstitutions()](#getSubstitutions--) | Mendapatkan informasi tentang font yang akan diganti pada rendering presentasi. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Mendapatkan informasi tentang font yang akan diganti selama rendering slide yang ditentukan. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Mengembalikan font yang disematkan dalam presentasi |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Menghapus font yang disematkan |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Menambahkan font yang disematkan. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Menambahkan font yang disematkan |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Mengganti font dalam presentasi |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Menentukan tingkat penyematan font dari array byte dan nama font yang diberikan. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Substitusi font yang digunakan saat merender Baca/tulis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Mengembalikan:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Substitusi font yang digunakan saat merender Baca/tulis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Mewakili koleksi pengguna dari aturan FontFallBack untuk mengelola koleksi font untuk substitusi yang tepat melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Mengambil koleksi aturan kosong atau sudah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // menambahkan aturan ke koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // atau 
>      // inisialisasi instance baru dari koleksi aturan
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Mewakili koleksi pengguna dari aturan FontFallBack untuk mengelola koleksi font untuk substitusi yang tepat melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Mengambil koleksi aturan kosong atau sudah diinisialisasi dari FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // menambahkan aturan ke koleksi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // atau 
>      // inisialisasi instance baru dari koleksi aturan
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
public abstract IFontData[] getFonts()
```


Mengembalikan font yang digunakan dalam presentasi

**Mengembalikan:**
com.aspose.slides.IFontData[] - Array font
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
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
| slides | int[] | Array indeks slide untuk mendapatkan informasi substitusi font, mulai dari 1. |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Koleksi semua substitusi font ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) untuk slide yang ditentukan.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Mengembalikan font yang disematkan dalam presentasi

**Mengembalikan:**
com.aspose.slides.IFontData[] - Font yang disematkan IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


Menghapus font yang disematkan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Menambahkan font yang disematkan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Aturan font yang disematkan [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Perhatikan bahwa ketika menyalin font, sebagian besar font dilindungi hak cipta. Pastikan terlebih dahulu lisensi font dan verifikasi bahwa font dapat dipindahkan secara bebas ke mesin lain. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Menambahkan font yang disematkan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | byte[] | Data font byte[] |
| embedFontRule | int | Aturan font yang disematkan [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Perhatikan bahwa ketika menambahkan font, sebagian besar font dilindungi hak cipta. Pastikan terlebih dahulu lisensi font dan verifikasi bahwa font dapat dipindahkan secara bebas ke mesin lain. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


Mengganti font dalam presentasi

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Font sumber |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Font tujuan |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Info substitusi font |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Koleksi info substitusi font |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Mengambil semua font yang digunakan dalam presentasi
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Dapatkan array byte yang mewakili gaya reguler font pertama dalam presentasi
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font yang berisi informasi tentang font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Gaya font yang data-nya akan diambil [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Mengembalikan:**
byte[] - Array byte yang berisi data font untuk gaya font yang ditentukan. Jika data font atau gaya tidak ditemukan, mengembalikan null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Menentukan tingkat penyematan font dari array byte dan nama font yang diberikan.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Mengambil semua font yang digunakan dalam presentasi
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Dapatkan array byte yang mewakili gaya reguler font pertama dalam presentasi
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Tentukan tingkat penyematan font
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