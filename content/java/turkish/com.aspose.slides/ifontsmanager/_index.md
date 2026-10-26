---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Sunum boyunca yazı tiplerini yönetir.
type: docs
url: /tr/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Sunum boyunca yazı tiplerini yönetir.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Render sırasında kullanılacak yazı tipi ikameleri Okuma/Yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Render sırasında kullanılacak yazı tipi ikameleri Okuma/Yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Kullanıcının, fallback işleviyle doğru ikameler sağlamak amacıyla yazı tipleri koleksiyonlarını yönetmek için FontFallBack kurallarının koleksiyonunu temsil eder Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Kullanıcının, fallback işleviyle doğru ikameler sağlamak amacıyla yazı tipleri koleksiyonlarını yönetmek için FontFallBack kurallarının koleksiyonunu temsil eder Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Sunumda kullanılan yazı tiplerini döndürür |
| [getSubstitutions()](#getSubstitutions--) | Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Sunuma gömülü yazı tiplerini döndürür |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Gömülü yazı tipini kaldırır |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Gömülü yazı tipini ekler. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Gömülü yazı tipini ekler |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sunumda yazı tipini değiştir |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Sunumda, [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) tarafından sağlanan bilgilerle yazı tipini değiştir |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Sunumda, [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) koleksiyonunda sağlanan bilgilerle yazı tipini değiştir |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Belirtilen bir yazı tipi stili ve font verisi için font verisini temsil eden bayt dizisini alır. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Verilen bayt dizisi ve font adından bir yazı tipinin gömme seviyesini belirler. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Render sırasında kullanılacak yazı tipi ikameleri Okuma/Yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Döndürür:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Render sırasında kullanılacak yazı tipi ikameleri Okuma/Yazma [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Kullanıcının, fallback işleviyle doğru ikameler sağlamak amacıyla yazı tipleri koleksiyonlarını yönetmek için FontFallBack kurallarının koleksiyonunu temsil eder Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Boş ya da önceden başlatılmış kurallar koleksiyonunu FontsManager'dan alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kurallar koleksiyonuna ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ya da 
>      // kurallar koleksiyonunun yeni bir örneğinin başlatılması
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kurallar koleksiyonuna ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve mevcut koleksiyonun FontsManager içinde yeniyle değiştirilmesi 
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

Kullanıcının, fallback işleviyle doğru ikameler sağlamak amacıyla yazı tipleri koleksiyonlarını yönetmek için FontFallBack kurallarının koleksiyonunu temsil eder Okuma/Yazma [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // kurallar koleksiyonuna ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // kurallar koleksiyonunun yeni bir örneğinin başlatılması
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // kurallar koleksiyonuna ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve mevcut koleksiyonun FontsManager içinde yeniyle değiştirilmesi 
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

Sunumda kullanılan yazı tiplerini döndürür

**Döndürür:**
com.aspose.slides.IFontData[] - Yazı tiplerinin bir dizisi

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

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
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

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
| slides | int[] | 1'den başlayan, font ikamesi bilgilerini almak için slayt indekslerinin bir dizisi. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Belirtilen slaytlar için tüm yazı tipi ikamelerinin bir koleksiyonu ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Sunuma gömülü yazı tiplerini döndürür

**Döndürür:**
com.aspose.slides.IFontData[] - Gömülü yazı tipleri IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Gömülü yazı tipini kaldırır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font veri nesnesi [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Gömülü yazı tipini ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font veri nesnesi [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Gömülü yazı tipi kuralı [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Herhangi bir yazı tipini kopyalarken, çoğu yazı tipinin telif hakkına sahip olduğunu unutmayın. Öncelikle bir yazı tipinin lisansını bulun ve başka bir makineye serbestçe aktarılabileceğini doğrulayın.

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Gömülü yazı tipini ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | byte[] | Yazı tipi verisi byte[] |
| embedFontRule | int | Gömülü yazı tipi kuralı [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Bir yazı tipi eklerken, çoğu yazı tipinin telif hakkına sahip olduğunu unutmayın. Öncelikle bir yazı tipinin lisansını bulun ve başka bir makineye serbestçe aktarılabileceğini doğrulayın.

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Sunumda yazı tipini değiştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Kaynak yazı tipi |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Hedef yazı tipi |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Sunumda, [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) tarafından sağlanan bilgilerle yazı tipini değiştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Yazı tipi ikamesi bilgisi |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Sunumda, [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) koleksiyonunda sağlanan bilgilerle yazı tipini değiştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Yazı tipi ikamesi bilgi koleksiyonu |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Belirtilen bir yazı tipi stili ve font verisi için font verisini temsil eden bayt dizisini alır.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Sunumda kullanılan tüm yazı tiplerini alır
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk yazı tipinin regular stilini temsil eden bayt dizisini alır
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Yazı tipi hakkında bilgileri içeren font veri nesnesi [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Verisinin alınacağı font stilinin tanımı [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Döndürür:**
byte[] - Belirtilen font stili için font verisini içeren bir bayt dizisi. Font verisi veya stil bulunamazsa null döndürür.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Verilen bayt dizisi ve font adından bir fontun gömme seviyesini belirler.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Sunumda kullanılan tüm yazı tiplerini alır
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk yazı tipinin regular stilini temsil eden bayt dizisini alır
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Fontun gömme seviyesini belirler
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