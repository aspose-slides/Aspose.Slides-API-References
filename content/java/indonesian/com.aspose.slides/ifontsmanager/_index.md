---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
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
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Mengembalikan font yang digunakan dalam presentasi |
| [getSubstitutions()](#getSubstitutions--) | Mengambil informasi tentang font yang akan diganti pada proses render presentasi. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Mengambil informasi tentang font yang akan diganti selama proses render slide yang ditentukan. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Mengembalikan font yang ter-embed dalam presentasi |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Menghapus font yang ter-embed |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Menambahkan font yang ter-embed. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Menambahkan font yang ter-embed |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Mengganti font dalam presentasi |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Mengambil array byte yang mewakili data font untuk gaya font dan data font yang ditentukan. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Menentukan tingkat embed font dari array byte dan nama font yang diberikan. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Menentukan apakah font yang terdaftar harus diprioritaskan dibandingkan font yang ter-embed dengan nama dan gaya yang sama. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Menentukan apakah font yang terdaftar harus diprioritaskan dibandingkan font yang ter-embed dengan nama dan gaya yang sama. |
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

Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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

Mewakili kumpulan aturan FontFallBack milik pengguna untuk mengelola koleksi font agar substitusi yang tepat dapat dilakukan melalui fungsi fallback Baca/tulis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
com.aspose.slides.IFontData[] - Sebuah array font
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Mengambil informasi tentang font yang akan diganti pada proses render presentasi.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Kumpulan semua substitusi font [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Mengambil informasi tentang font yang akan diganti selama proses render slide yang ditentukan.

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
| slides | int[] | Sebuah array indeks slide untuk mengambil informasi substitusi font, dimulai dari 1. |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Kumpulan semua substitusi font ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) untuk slide yang ditentukan.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Mengembalikan font yang ter-embed dalam presentasi

**Mengembalikan:**
com.aspose.slides.IFontData[] - Font ter-embed IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Menghapus font yang ter-embed

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Menambahkan font yang ter-embed.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Aturan font ter-embed [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Perlu diingat saat menyalin font apa pun bahwa sebagian besar font dilindungi hak cipta. Pertama, temukan lisensi font tersebut terlebih dahulu dan verifikasi bahwa mereka dapat dipindahkan secara bebas ke mesin lain. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Menambahkan font yang ter-embed

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | byte[] | Data font  byte[]  |
| embedFontRule | int | Aturan font ter-embed [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Perlu diingat saat menambahkan font apa pun bahwa sebagian besar font dilindungi hak cipta. Pertama, temukan lisensi font tersebut terlebih dahulu dan verifikasi bahwa mereka dapat dipindahkan secara bebas ke mesin lain. |

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
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informasi substitusi font |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Mengganti font dalam presentasi menggunakan informasi yang disediakan dalam koleksi [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Koleksi informasi substitusi font |

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
>      // Dapatkan array byte yang mewakili gaya reguler dari font pertama dalam presentasi
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objek data font yang berisi informasi tentang font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Gaya font yang datanya ingin diambil [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Mengembalikan:**
byte[] - Sebuah array byte yang berisi data font untuk gaya font yang ditentukan. Jika data font atau gaya tidak ditemukan, mengembalikan null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Menentukan tingkat embed font dari array byte dan nama font yang diberikan.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Mengambil semua font yang digunakan dalam presentasi
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Dapatkan array byte yang mewakili gaya reguler dari font pertama dalam presentasi
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Menentukan tingkat embed font
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
int - Tingkat embed font yang ditentukan.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Menentukan apakah font yang terdaftar harus diprioritaskan dibandingkan font yang ter-embed dengan nama dan gaya yang sama. Ketika diaktifkan, font ter-embed yang cocok sementara diganti dengan font terdaftar yang bersesuaian saat ekspor.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Default adalah **false** .

**Mengembalikan:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Menentukan apakah font yang terdaftar harus diprioritaskan dibandingkan font yang ter-embed dengan nama dan gaya yang sama. Ketika diaktifkan, font ter-embed yang cocok sementara diganti dengan font terdaftar yang bersesuaian saat ekspor.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Default adalah **false** .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |