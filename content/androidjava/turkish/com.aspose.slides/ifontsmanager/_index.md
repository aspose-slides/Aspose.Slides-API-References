---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Sunum boyunca yazı tiplerini yönetir.
type: docs
url: /tr/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Sunum boyunca yazı tiplerini yönetir.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Render sırasında kullanılacak yazı tipi ikameleri. Okuma/yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Render sırasında kullanılacak yazı tipi ikameleri. Okuma/yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Kullanıcının font yedekleme kurallarının koleksiyonunu temsil eder; uygun ikameler için yedekleme işlevselliği ile font koleksiyonlarını yönetir. Okuma/yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Kullanıcının font yedekleme kurallarının koleksiyonunu temsil eder; uygun ikameler için yedekleme işlevselliği ile font koleksiyonlarını yönetir. Okuma/yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Sunumda kullanılan fontları döndürür |
| [getSubstitutions()](#getSubstitutions--) | Sunumun render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Belirtilen slaytların render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Sunumda gömülü fontları döndürür |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Gömülü fontu kaldırır |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Gömülü fontu ekler. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Gömülü fontu ekler |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sunumda fontu değiştirir |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) içinde sağlanan bilgilerle sunumda fontu değiştirir |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) koleksiyonunda sağlanan bilgilerle sunumda fontu değiştirir |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Belirli bir font stiline ve font verisine ait byte dizisini geri alır. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Verilen byte dizisi ve font adıyla bir fontun gömme seviyesini belirler. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Render sırasında kullanılacak yazı tipi ikameleri. Okuma/yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Döndürür:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Render sırasında kullanılacak yazı tipi ikameleri. Okuma/yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Kullanıcının font yedekleme kurallarının koleksiyonunu temsil eder; uygun ikameler için yedekleme işlevselliği ile font koleksiyonlarını yönetir. Okuma/yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // ve mevcut koleksiyonun FontsManager içinde yenisiyle değiştirilmesi 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Kullanıcının font yedekleme kurallarının koleksiyonunu temsil eder; uygun ikameler için yedekleme işlevselliği ile font koleksiyonlarını yönetir. Okuma/yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // kurallar koleksiyonunun yeni bir örneğini başlatma
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve mevcut koleksiyonu FontsManager içinde yenisiyle değiştirme 
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
public abstract IFontData[] getFonts()
```


Sunumda kullanılan fontları döndürür

**Döndürür:**
com.aspose.slides.IFontData[] - Fontların bir dizisi
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Sunumun render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Tüm font ikamelerinin koleksiyonu [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Belirtilen slaytların render edilmesi sırasında değiştirilecek fontlar hakkında bilgi alır.

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
| slides | int[] | 1'den başlayan slayt indeksleri dizisi; font ikameleri bilgisi alınacak slaytlar. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Belirtilen slaytlar için tüm font ikamelerinin koleksiyonu ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Sunumda gömülü fontları döndürür

**Döndürür:**
com.aspose.slides.IFontData[] - Gömülü fontlar IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


Gömülü fontu kaldırır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font veri nesnesi [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Gömülü fontu ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font veri nesnesi [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Gömülü font kuralı [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Gömülü fontları kopyalarken çoğu fontun telif hakkı olduğunu unutmayın. Önceden fontun lisansını kontrol edin ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Gömülü fontu ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | byte[] | Font veri byte[] |
| embedFontRule | int | Gömülü font kuralı [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Yeni font eklerken çoğu fontun telif hakkı olduğunu unutmayın. Önceden fontun lisansını kontrol edin ve başka bir makineye serbestçe aktarılabileceğini doğrulayın. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


Sunumda fontu değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Kaynak font |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Hedef font |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) içinde sağlanan bilgilerle sunumda fontu değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Font ikame bilgisi |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) koleksiyonunda sağlanan bilgilerle sunumda fontu değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Font ikame bilgisi koleksiyonu |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Belirli bir font stiline ve font verisine ait byte dizisini geri alır.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Retrieve all fonts used in the presentation
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Get the byte array representing the regular style of the first font in the presentation
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font verisi nesnesi; font hakkında bilgi içerir [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Veri alınacak font stilinin kodu [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Döndürür:**
byte[] - Belirtilen font stili için font verisini içeren byte dizisi. Font verisi veya stil bulunamazsa null döner.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Verilen byte dizisi ve font adıyla bir fontun gömme seviyesini belirler.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Sunumda kullanılan tüm fontları al
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk fontun normal stilini temsil eden byte dizisini al
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Fontun gömme seviyesini belirle
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontBytes | byte[] | Font verisini içeren byte dizisi. |
| fontName | java.lang.String | Fontun adı. |

**Döndürür:**
int - Belirtilen fontun gömme seviyesi.