---
title: FontsManager
second_title: Aspose.Slides için Java API Referansı
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
>      // Değiştirilecek kaynak fontu yükle
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
```
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Renderleme sırasında kullanılacak yazı tipi ikameleri. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Renderleme sırasında kullanılacak yazı tipi ikameleri. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tipleri koleksiyonlarını yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunabilir/Yazılabilir [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tipleri koleksiyonlarını yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunabilir/Yazılabilir [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Sunumda kullanılan yazı tiplerini döndürür |
| [getSubstitutions()](#getSubstitutions--) | Sunumun renderlenmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Belirtilen slaytların renderlenmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Kayıtlı yazı tiplerinin, aynı ad ve stile sahip gömülü yazı tiplerine göre tercih edilip edilmeyeceğini belirtir. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Kayıtlı yazı tiplerinin, aynı ad ve stile sahip gömülü yazı tiplerine göre tercih edilip edilmeyeceğini belirtir. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Sunumda gömülü olan yazı tiplerini döndürür |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Gömülü yazı tipini kaldırır |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Gömülü yazı tipini ekler |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Gömülü yazı tipini ekler |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sunumda yazı tipini değiştirir |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) içinde sağlanan bilgilerle sunumda yazı tipini değiştirir |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) koleksiyonundaki bilgilerle sunumda yazı tipini değiştirir |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Belirli bir yazı tipi stili ve yazı tipi verisi için font verisini temsil eden bayt dizisini alır. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Verilen bayt dizisi ve yazı tipi adı üzerinden bir yazı tipinin gömme seviyesini belirler. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```


Renderleme sırasında kullanılacak yazı tipi ikameleri. Okunabilir/Yazılabilir [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Döndürür:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Renderleme sırasında kullanılacak yazı tipi ikameleri. Okunabilir/Yazılabilir [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tipleri koleksiyonlarını yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunabilir/Yazılabilir [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alma
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // kurallar koleksiyonunun yeni bir örneğinin başlatılması
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve FontsManager'da mevcut koleksiyonu yenisiyle değiştirme 
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


Kullanıcının, yedekleme işleviyle doğru ikameler için yazı tipleri koleksiyonlarını yönetmek üzere FontFallBack kurallarının koleksiyonunu temsil eder. Okunabilir/Yazılabilir [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alma
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // kurallar koleksiyonunun yeni bir örneğinin başlatılması
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


Sunumun renderlenmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

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


Belirtilen slaytların renderlenmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

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
| slides | int[] | 1’den başlayarak, font ikamesi bilgisinin alınacağı slayt indekslerinin dizisi. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Belirtilen slaytlar için tüm font ikamelerinin bir koleksiyonu ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```


Kayıtlı yazı tiplerinin, aynı ad ve stile sahip gömülü yazı tiplerine göre tercih edilip edilmeyeceğini belirtir. Etkinleştirildiğinde, eşleşen gömülü yazı tipleri dışa aktarım sırasında geçici olarak ilgili kayıtlı yazı tipleriyle değiştirilir.

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

Varsayılan **false**.

**Döndürür:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```


Kayıtlı yazı tiplerinin, aynı ad ve stile sahip gömülü yazı tiplerine göre tercih edilip edilmeyeceğini belirtir. Etkinleştirildiğinde, eşleşen gömülü yazı tipleri dışa aktarım sırasında geçici olarak ilgili kayıtlı yazı tipleriyle değiştirilir.

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

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

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


[FontSubstRule](../../com.aspose.slides/fontsubstrule) içinde sağlanan bilgilerle sunumda yazı tipini değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Yazı tipi ikamesi bilgisi |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```


[FontSubstRule](../../com.aspose.slides/fontsubstrule) koleksiyonundaki bilgilerle sunumda yazı tipini değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Yazı tipi ikamesi kuralları koleksiyonu |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Belirli bir yazı tipi stili ve font verisi için font verisini temsil eden bayt dizisini alır.

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
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font verisi nesnesi, font [IFontData](../../com.aspose.slides/ifontdata) hakkındaki bilgileri içerir. |
| fontStyle | int | İstenen font stilinin numarası [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Döndürür:**
byte[] - Belirtilen font stilinin font verisini içeren bir bayt dizisi. Font verisi ya da stil bulunamazsa, null döndürülür.
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