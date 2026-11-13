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
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Render ederken kullanılacak yazı tipi ikameleri Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Render ederken kullanılacak yazı tipi ikameleri Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; düşüş işlevselliği ile doğru ikameler için koleksiyonları yönetir Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; düşüş işlevselliği ile doğru ikameler için koleksiyonları yönetir Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Sunumda kullanılan yazı tiplerini döndürür |
| [getSubstitutions()](#getSubstitutions--) | Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Sunumda gömülü olan yazı tiplerini döndürür |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Gömülü yazı tipini kaldırır |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Gömülü yazı tipini ekler. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Gömülü yazı tipini ekler |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Sunumda yazı tipini değiştirir |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Sunumda yazı tipini [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) içinde verilen bilgilerle değiştirir |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Sunumda yazı tipini [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) koleksiyonundaki bilgilerle değiştirir |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Belirli bir font stiline ve font verisine ait byte dizisini alır. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Verilen byte dizisi ve font adı üzerinden bir fontun gömme seviyesini belirler. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Kayıtlı fontların aynı isim ve stile sahip gömülü fontlara göre tercih edilip edilmediğini belirler. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Kayıtlı fontların aynı isim ve stile sahip gömülü fontlara göre tercih edilip edilmediğini belirler. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Render ederken kullanılacak yazı tipi ikameleri Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Döndürür:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Render ederken kullanılacak yazı tipi ikameleri Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |
### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; düşüş işlevselliği ile doğru ikameler için koleksiyonları yönetir Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // Kurallar koleksiyonunun yeni bir örneğini başlatma
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ve mevcut koleksiyonu FontsManager içinde yenisiyle değiştirme 
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

Kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; düşüş işlevselliği ile doğru ikameler için koleksiyonları yönetir Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Kuralları koleksiyona ekleme
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // veya 
>      // Kurallar koleksiyonunun yeni bir örneğini başlatma
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Kuralları koleksiyona ekleme
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
| slides | int[] | Font ikame bilgilerini almak için kullanılacak slayt indekslerinin bir dizisi, 1'den başlayarak. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Belirtilen slaytlar için tüm font ikamelerinin bir koleksiyonu [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Sunumda gömülü olan yazı tiplerini döndürür

**Döndürür:**
com.aspose.slides.IFontData[] - Gömülü fontlar IFontData[]
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
| embedFontRule | int | Gömülü font kuralı [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------
Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Gömülü fontu ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | byte[] | Font verisi byte[] |
| embedFontRule | int | Gömülü font kuralı [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------
Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |
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

Sunumda fontu [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) içinde verilen bilgilerle değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Font ikamesi bilgisi |
### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Sunumda fontu [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) koleksiyonundaki bilgilerle değiştirir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Font ikamesi bilgi koleksiyonu |
### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Belirtilen font stiline ve font verisine ait byte dizisini alır.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Sunumda kullanılan tüm fontları al
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Sunumdaki ilk fontun normal stilini temsil eden byte dizisini al
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font hakkında bilgi içeren font veri nesnesi [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Veri alınacak font stilinin türü [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Döndürür:**
byte[] - Belirtilen font stilinin font verisini içeren bir byte dizisi. Font verisi veya stil bulunamazsa, null döner.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Verilen byte dizisi ve font adı üzerinden bir fontun gömme seviyesini belirler.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Retrieve all fonts used in the presentation
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Get the byte array representing the regular style of the first font in the presentation
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Determine the embedding level of the font
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
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Kayıtlı fontların aynı isim ve stile sahip gömülü fontlara göre tercih edilip edilmediğini belirler. Etkinleştirildiğinde, eşleşen gömülü fontlar dışa aktarım sırasında geçici olarak ilgili kayıtlı fontlarla değiştirilir.

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

Default is  **false** .

**Döndürür:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Kayıtlı fontların aynı isim ve stile sahip gömülü fontlara göre tercih edilip edilmediğini belirler. Etkinleştirildiğinde, eşleşen gömülü fontlar dışa aktarım sırasında geçici olarak ilgili kayıtlı fontlarla değiştirilir.

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

Default is  **false** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |