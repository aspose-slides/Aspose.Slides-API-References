---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /hi/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

प्रेज़ेंटेशन में फ़ॉन्ट्स का प्रबंधन करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | रेंडरिंग के समय उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)। |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | रेंडरिंग के समय उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)। |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | उपयोगकर्ता के फ़ॉन्टफ़ॉलबैक नियमों के संग्रह को दर्शाता है जो फ़ॉन्ट संग्रह को उचित प्रतिस्थापनों के लिए फ़ॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)। |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | उपयोगकर्ता के फ़ॉन्टफ़ॉलबैक नियमों के संग्रह को दर्शाता है जो फ़ॉन्ट संग्रह को उचित प्रतिस्थापनों के लिए फ़ॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)। |
| [getFonts()](#getFonts--) | प्रेज़ेंटेशन में उपयोग किए गए फ़ॉन्ट्स को पुनः प्राप्त करता है |
| [getSubstitutions()](#getSubstitutions--) | प्रेज़ेंटेशन के रेंडरिंग पर बदलने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान बदलने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | प्रेज़ेंटेशन में एम्बेडेड फ़ॉन्ट्स को पुनः प्राप्त करता है |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | एम्बेडेड फ़ॉन्ट को हटाता है |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | एम्बेडेड फ़ॉन्ट को जोड़ता है। |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | एम्बेडेड फ़ॉन्ट जोड़ता है |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | प्रेज़ेंटेशन में फ़ॉन्ट बदलें |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) में प्रदान की गई सूचना का उपयोग करके प्रेज़ेंटेशन में फ़ॉन्ट बदलें |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) के संग्रह में प्रदान की गई सूचना का उपयोग करके प्रेज़ेंटेशन में फ़ॉन्ट बदलें |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का बाइट एरे प्राप्त करता है। |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर को निर्धारित करता है। |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | यह निर्धारित करता है कि समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर पंजीकृत फ़ॉन्ट्स को प्राथमिकता देनी चाहिए या नहीं। |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | यह निर्धारित करता है कि समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर पंजीकृत फ़ॉन्ट्स को प्राथमिकता देनी चाहिए या नहीं। |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

रेंडरिंग के समय उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)।

**रिटर्न:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

रेंडरिंग के समय उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

उपयोगकर्ता के फ़ॉन्टफ़ॉलबैक नियमों के संग्रह को दर्शाता है जो फ़ॉन्ट संग्रह को उचित प्रतिस्थापनों के लिए फ़ॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // फ़ॉन्ट्समैनेजर से खाली या पूर्व-आरम्भित नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // या 
>      // नियम संग्रह के नए उदाहरण को आरम्भ करना
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // और फ़ॉन्ट्समैनेजर में मौजूदा संग्रह को नई संग्रह से प्रतिस्थापित करना 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

उपयोगकर्ता के फ़ॉन्टफ़ॉलबैक नियमों के संग्रह को दर्शाता है जो फ़ॉन्ट संग्रह को उचित प्रतिस्थापनों के लिए फ़ॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // फ़ॉन्ट्समैनेजर से खाली या पहले से प्रारम्भित नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // या 
>      // नियम संग्रह के नए उदाहरण का आरम्भ करना
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // और फ़ॉन्ट्समैनेजर में मौजूदा संग्रह को नई से बदलना 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

प्रेज़ेंटेशन में उपयोग किए गए फ़ॉन्ट्स को पुनः प्राप्त करता है

**रिटर्न:**
com.aspose.slides.IFontData[] - फ़ॉन्ट्स का एरे

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

प्रेज़ेंटेशन के रेंडरिंग पर बदलने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है।

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


**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - सभी फ़ॉन्ट प्रतिस्थापन [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) का संग्रह।

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान बदलने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slides | int[] | उन स्लाइड इंडेक्सों का एरे जिसके लिए फ़ॉन्ट प्रतिस्थापन जानकारी प्राप्त करनी है, 1 से शुरू। |

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - निर्दिष्ट स्लाइड्स के लिए सभी फ़ॉन्ट प्रतिस्थापन ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) का संग्रह।

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

प्रेज़ेंटेशन में एम्बेडेड फ़ॉन्ट्स को पुनः प्राप्त करता है

**रिटर्न:**
com.aspose.slides.IFontData[] - एम्बेडेड फ़ॉन्ट्स IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

एम्बेडेड फ़ॉन्ट को हटाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | फ़ॉन्ट डेटा ऑब्जेक्ट [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

एम्बेडेड फ़ॉन्ट को जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | फ़ॉन्ट डेटा ऑब्जेक्ट [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | एम्बेडेड फ़ॉन्ट नियम [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

ध्यान दें कि अधिकांश फ़ॉन्ट्स कॉपीराइटेड होते हैं। किसी फ़ॉन्ट को कॉपी करने से पहले उसके लाइसेंस को जाँचें और सुनिश्चित करें कि इसे दूसरी मशीन पर स्वतंत्र रूप से स्थानांतरित किया जा सकता है। |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

एम्बेडेड फ़ॉन्ट को जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | byte[] | फ़ॉन्ट डेटा  byte[]  |
| embedFontRule | int | एम्बेडेड फ़ॉन्ट नियम [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

ध्यान दें कि अधिकांश फ़ॉन्ट्स कॉपीराइटेड होते हैं। किसी फ़ॉन्ट को जोड़ने से पहले उसके लाइसेंस को जाँचें और सुनिश्चित करें कि इसे दूसरी मशीन पर स्वतंत्र रूप से स्थानांतरित किया जा सकता है। |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

प्रेज़ेंटेशन में फ़ॉन्ट बदलें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | स्रोत फ़ॉन्ट |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | गंतव्य फ़ॉन्ट |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) में प्रदान की गई सूचना का उपयोग करके प्रेज़ेंटेशन में फ़ॉन्ट बदलें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | फ़ॉन्ट प्रतिस्थापन जानकारी |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) के संग्रह में प्रदान की गई सूचना का उपयोग करके प्रेज़ेंटेशन में फ़ॉन्ट बदलें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | फ़ॉन्ट प्रतिस्थापन जानकारी संग्रह |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का बाइट एरे प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // प्रेज़ेंटेशन में उपयोग किए गए सभी फ़ॉन्ट्स प्राप्त करें
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // प्रेज़ेंटेशन में पहले फ़ॉन्ट की नियमित शैली का बाइट एरे प्राप्त करें
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | फ़ॉन्ट डेटा ऑब्जेक्ट जिसमें फ़ॉन्ट [IFontData](../../com.aspose.slides/ifontdata) के बारे में जानकारी होती है। |
| fontStyle | int | वह फ़ॉन्ट शैली जिसके लिए डेटा प्राप्त किया जाना है [FontStyleType](../../com.aspose.slides/fontstyletype)। |

**रिटर्न:**
byte[] - निर्दिष्ट फ़ॉन्ट शैली के फ़ॉन्ट डेटा वाला बाइट एरे। यदि फ़ॉन्ट डेटा या शैली नहीं मिली, तो null लौटाता है।

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर को निर्धारित करता है।

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // प्रेज़ेंटेशन में उपयोग किए गए सभी फ़ॉन्ट्स प्राप्त करें
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // प्रेज़ेंटेशन में पहले फ़ॉन्ट की नियमित शैली का बाइट एरे प्राप्त करें
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // फ़ॉन्ट के एम्बेडिंग स्तर का निर्धारण करें
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontBytes | byte[] | फ़ॉन्ट डेटा युक्त बाइट एरे। |
| fontName | java.lang.String | फ़ॉन्ट का नाम। |

**रिटर्न:**
int - निर्दिष्ट फ़ॉन्ट का एम्बेडिंग स्तर।

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

निर्धारित करता है कि समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर पंजीकृत फ़ॉन्ट्स को प्राथमिकता देनी चाहिए या नहीं। सक्षम होने पर, निर्यात के दौरान मिलते-जुलते एम्बेडेड फ़ॉन्ट्स को अस्थायी रूप से संबंधित पंजीकृत फ़ॉन्ट्स से बदल दिया जाता है।

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

डिफ़ॉल्ट **false** है।

**रिटर्न:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

निर्धारित करता है कि समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर पंजीकृत फ़ॉन्ट्स को प्राथमिकता देनी चाहिए या नहीं। सक्षम होने पर, निर्यात के दौरान मिलते-जुलते एम्बेडेड फ़ॉन्ट्स को अस्थायी रूप से संबंधित पंजीकृत फ़ॉन्ट्स से बदल दिया जाता है।

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

डिफ़ॉल्ट **false** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |