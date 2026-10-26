---
title: FontsManager
second_title: Java API Referansı ile Android için Aspose.Slides
description: Sunum boyunca yazı tiplerini yönetir.
type: docs
url: /tr/com.aspose.slides/fontsmanager/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Sunum boyunca yazı tiplerini yönetir.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Sunumu yükle
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Değiştirilecek kaynak yazı tipini yükle
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
>      // Sunumu kaydet
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Rendering sırasında kullanılacak yazı tipi ikameleri. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Rendering sırasında kullanılacak yazı tipi ikameleri. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Fallback işleviyle doğru ikameler için yazı tiplerinin koleksiyonlarını yönetmek üzere FontFallBack kurallarının bir kullanıcının koleksiyonunu temsil eder. Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Fallback işleviyle doğru ikameler için yazı tiplerinin koleksiyonlarını yönetmek üzere FontFallBack kurallarının bir kullanıcının koleksiyonunu temsil eder. Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Sunumda kullanılan yazı tiplerini döndürür |
| [getSubstitutions()](#getSubstitutions--) | Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgiyi alır. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgiyi alır. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Sunuma gömülü yazı tiplerini döndürür |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Gömülü yazı tipini kaldırır |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Gömülü yazı tipini ekler |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Gömülü yazı tipini ekler |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sunumda yazı tipini değiştir |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Sunumda yazı tipini, [FontSubstRule](../../com.aspose.slides/fontsubstrule) içinde sağlanan bilgiyi kullanarak değiştir |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Sunumda yazı tipini, [FontSubstRule](../../com.aspose.slides/fontsubstrule) koleksiyonunda sağlanan bilgiyi kullanarak değiştir |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Belirli bir yazı tipi stili ve font veri seti için font verisini temsil eden bayt dizisini alır. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Verilen bayt dizisi ve font adı üzerinden bir fontun gömme seviyesini belirler. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Rendering sırasında kullanılacak yazı tipi ikameleri. Okuma/Yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Döndürür:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Rendering sırasında kullanılacak yazı tipi ikameleri. Okuma/Yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Fallback işleviyle doğru ikameler için yazı tiplerinin koleksiyonlarını yönetmek üzere FontFallBack kurallarının bir kullanıcının koleksiyonunu temsil eder. Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunun alınması
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kuralların koleksiyona eklenmesi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // kurallar koleksiyonunun yeni bir örneğinin başlatılması
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kuralların koleksiyona eklenmesi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // FontsManager'da mevcut koleksiyonun yeni olanla değiştirilmesi 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Fallback işleviyle doğru ikameler için yazı tiplerinin koleksiyonlarını yönetmek üzere FontFallBack kurallarının bir kullanıcının koleksiyonunu temsil eder. Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunun alınması
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kuralların koleksiyona eklenmesi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // kurallar koleksiyonunun yeni bir örneğinin başlatılması
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kuralların koleksiyona eklenmesi
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // FontsManager'da mevcut koleksiyonun yeni olanla değiştirilmesi 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Sunumda kullanılan yazı tiplerini döndürür

**Döndürür:**
com.aspose.slides.IFontData[] - Yazı tiplerinin bir dizisi

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgiyi alır.

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


**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Tüm yazı tipi ikamelerinin koleksiyonu [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgiyi alır.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slides | int[] | 1'den başlayan, font ikame bilgilerini almak için slayt indekslerinin bir dizisi. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Belirtilen slaytlar için tüm font ikamelerinin bir koleksiyonu ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Sunuma gömülü yazı tiplerini döndürür

**Döndürür:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Gömülü yazı tipini kaldırır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Gömülü yazı tipini ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Gömülü yazı tipini ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Sunumda yazı tipini değiştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Kaynak yazı tipi |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Hedef yazı tipi |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Sunumda, [FontSubstRule](../../com.aspose.slides/fontsubstrule) içinde sağlanan bilgiyi kullanarak yazı tipini değiştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Yazı tipi ikame bilgisi |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Sunumda, [FontSubstRule](../../com.aspose.slides/fontsubstrule) koleksiyonunda sağlanan bilgiyi kullanarak yazı tipini değiştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Yazı tipi ikame kuralları koleksiyonu |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Belirli bir font stili ve font veri seti için font verisini temsil eden bayt dizisini alır.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Sunumda kullanılan tüm yazı tiplerini al
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk yazı tipinin normal stilini temsil eden bayt dizisini al
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font [IFontData](../../com.aspose.slides/ifontdata) hakkında bilgi içeren font veri nesnesi. |
| fontStyle | int | Verinin alınacağı font stilinin biçimi [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Döndürür:**
byte[] - Belirtilen font stili için font verisini içeren bir bayt dizisi. Eğer font verisi veya stil bulunamazsa, null döndürür.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Verilen bayt dizisi ve font adı üzerinden bir fontun gömme seviyesini belirler.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Sunumda kullanılan tüm yazı tiplerini al
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk yazı tipinin normal stilini temsil eden bayt dizisini al
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Yazı tipinin gömme seviyesini belirle
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontBytes | byte[] | Font verisini içeren bayt dizisi. |
| fontName | java.lang.String | Fontun adı. |

**Döndürür:**
int - Belirtilen fontun gömme seviyesi.