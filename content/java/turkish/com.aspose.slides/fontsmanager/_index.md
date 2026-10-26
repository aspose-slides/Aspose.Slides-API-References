---
title: FontsManager
second_title: Aspose.Slides for Java API Referansı
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
>          // Sunumu kaydet
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Renderlama sırasında kullanılacak yazı tipi ikameleri. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Renderlama sırasında kullanılacak yazı tipi ikameleri. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tiplerini yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunur/Yazılır [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tiplerini yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunur/Yazılır [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Sunumda kullanılan yazı tiplerini döndürür |
| [getSubstitutions()](#getSubstitutions--) | Sunumun renderlanması sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Belirtilen slaytların renderlanması sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Sunumda gömülü olan yazı tiplerini döndürür |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Gömülü yazı tipini kaldırır |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Gömülü yazı tipini ekler |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Gömülü yazı tipini ekler |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sunumda yazı tipini değiştirir |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) içinde sağlanan bilgiler kullanılarak sunumda yazı tipi değiştirilir |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) koleksiyonunda sağlanan bilgiler kullanılarak sunumda yazı tipi değiştirilir |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Belirli bir yazı tipi stili ve yazı tipi verisi için yazı tipi verilerini temsil eden bayt dizisini alır. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Verilen bayt dizisi ve yazı tipi adından bir yazı tipinin gömme seviyesini belirler. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Renderlama sırasında kullanılacak yazı tipi ikameleri. Okunur/Yazılır [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Döndürür:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Renderlama sırasında kullanılacak yazı tipi ikameleri. Okunur/Yazılır [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tiplerini yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunur/Yazılır [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş ya da önceden başlatılmış kurallar koleksiyonunu alma
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ya da 
>      // kurallar koleksiyonunun yeni bir örneğini başlatma
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve mevcut koleksiyonu FontsManager'da yenisiyle değiştirme 
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

Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tiplerini yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunur/Yazılır [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alma
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ya da 
>      // kurallar koleksiyonunun yeni bir örneğini başlatma
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve mevcut koleksiyonu FontsManager'da yenisiyle değiştirme 
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

Sunumun renderlanması sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

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

Belirtilen slaytların renderlanması sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

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
| slides | int[] | Bilgi alınacak slayt indekslerinin (1'den başlayan) bir dizisi. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Belirtilen slaytlar için tüm yazı tipi ikamelerinin koleksiyonu ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Sunumda gömülü olan yazı tiplerini döndürür

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

Sunumda yazı tipini değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Kaynak yazı tipi |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Hedef yazı tipi |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) içinde sağlanan bilgiler kullanılarak sunumda yazı tipi değiştirilir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Yazı tipi ikama bilgisi |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) koleksiyonunda sağlanan bilgiler kullanılarak sunumda yazı tipi değiştirilir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Yazı tipi ikama kuralları koleksiyonu |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Belirli bir yazı tipi stili ve yazı tipi verisi için yazı tipi verilerini temsil eden bayt dizisini alır.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Sunumda kullanılan tüm yazı tiplerini al
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk yazı tipinin regular stilini temsil eden bayt dizisini al
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | [IFontData](../../com.aspose.slides/ifontdata) hakkında bilgi içeren yazı tipi veri nesnesi. |
| fontStyle | int | Alınacak veri için yazı tipi stilinin türü [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Döndürür:**
byte[] - Belirtilen yazı tipi stili için yazı tipi verilerini içeren bir bayt dizisi. Yazı tipi verisi veya stil bulunamazsa, null döndürür.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Verilen bayt dizisi ve yazı tipi adından bir yazı tipinin gömme seviyesini belirler.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Sunumda kullanılan tüm yazı tiplerini al
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk yazı tipinin regular stilini temsil eden bayt dizisini al
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
| fontBytes | byte[] | Yazı tipi verilerini içeren bayt dizisi. |
| fontName | java.lang.String | Yazı tipinin adı. |

**Döndürür:**
int - Belirtilen yazı tipinin gömme seviyesi.