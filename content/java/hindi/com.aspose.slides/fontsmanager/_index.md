---
title: FontsManager
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति में फ़ॉन्ट्स का प्रबंधन करता है।
type: docs
url: /hi/com.aspose.slides/fontsmanager/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

प्रस्तुति में फ़ॉन्ट्स को प्रबंधित करता है।

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // प्रस्तुति लोड करें
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // बदले जाने वाले स्रोत फ़ॉन्ट को लोड करें
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
>      // प्रस्तुति को सहेजें
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | रेंडरिंग के समय उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन। |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | रेंडरिंग के समय उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन। |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | एक उपयोगकर्ता की फ़ॉन्टफ़ॉलबैक नियमों का संग्रह दर्शाता है जो फ़ॉन्ट्स के संग्रह को उचित प्रतिस्थापन के लिए फॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है। Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | एक उपयोगकर्ता की फ़ॉन्टफ़ॉलबैक नियमों का संग्रह दर्शाता है जो फ़ॉन्ट्स के संग्रह को उचित प्रतिस्थापन के लिए फॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है। Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | प्रस्तुति में उपयोग किए गए फ़ॉन्ट्स को लौटाता है। |
| [getSubstitutions()](#getSubstitutions--) | प्रस्तुति के रेंडरिंग के दौरान प्रतिस्थापित किए जाने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान प्रतिस्थापित किए जाने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | निर्दिष्ट करता है कि क्या पंजीकृत फ़ॉन्ट्स को समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर प्राथमिकता दी जानी चाहिए। |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | निर्दिष्ट करता है कि क्या पंजीकृत फ़ॉन्ट्स को समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर प्राथमिकता दी जानी चाहिए। |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | प्रस्तुति में एम्बेडेड फ़ॉन्ट्स को लौटाता है। |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | एम्बेडेड फ़ॉन्ट को हटाता है। |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | एंबेडेड फ़ॉन्ट जोड़ता है। |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | एंबेडेड फ़ॉन्ट जोड़ता है। |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | प्रस्तुति में फ़ॉन्ट बदलें। |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | प्रस्तुति में फ़ॉन्ट बदलें, जो [FontSubstRule](../../com.aspose.slides/fontsubstrule) में प्रदान की गई जानकारी का उपयोग करता है। |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | प्रस्तुति में फ़ॉन्ट बदलें, जो [FontSubstRule](../../com.aspose.slides/fontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग करता है। |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का बाइट एरे प्राप्त करता है। |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर का निर्धारण करता है। |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

रेंडरिंग के समय उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन। Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**रिटर्न:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

रेंडरिंग के समय उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन। Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

एक उपयोगकर्ता के फ़ॉन्टफ़ॉलबैक नियमों के संग्रह को दर्शाता है जो फ़ॉन्ट संग्रहों को उचित प्रतिस्थापन के लिए फॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है। Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager से खाली या पहले से आरंभित नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // नियमों को संग्रह में जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // या 
>      // नियम संग्रह की नई इंस्टेंस का आरंभ करना
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // नियमों को संग्रह में जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // और FontsManager में मौजूदा संग्रह को नई से बदलना 
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
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

एक उपयोगकर्ता के फ़ॉन्टफ़ॉलबैक नियमों के संग्रह को दर्शाता है जो फ़ॉन्ट संग्रहों को उचित प्रतिस्थापन के लिए फॉलबैक कार्यक्षमता द्वारा प्रबंधित करता है। Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager से खाली या पहले से आरंभीकृत नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // नियमों को संग्रह में जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // या 
>      // नियम संग्रह की नई इंस्टेंस का आरंभ करना
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // नियमों को संग्रह में जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // और FontsManager में मौजूदा संग्रह को नई से बदलना 
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
public final IFontData[] getFonts()
```

प्रस्तुति में उपयोग किए गए फ़ॉन्ट्स को लौटाता है।

**रिटर्न:**
com.aspose.slides.IFontData[] - फ़ॉन्ट्स का एक एरे

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

प्रस्तुति के रेंडरिंग के दौरान प्रतिस्थापित किए जाने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है।

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - सभी फ़ॉन्ट प्रतिस्थापनों का संग्रह [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान प्रतिस्थापित किए जाने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है।

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
| slides | int[] | फ़ॉन्ट प्रतिस्थापन जानकारी प्राप्त करने के लिए स्लाइड इंडेक्स की एरे, 1 से शुरू। |

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - निर्दिष्ट स्लाइड्स के लिए सभी फ़ॉन्ट प्रतिस्थापनों का संग्रह ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))।

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

निर्दिष्ट करता है कि क्या पंजीकृत फ़ॉन्ट्स को समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर प्राथमिकता दी जानी चाहिए। जब सक्रिय होता है, तो मिलते-जुलते एम्बेडेड फ़ॉन्ट्स को अस्थायी रूप से संबंधित पंजीकृत फ़ॉन्ट्स से बदल दिया जाता है।

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

डिफ़ॉल्ट **false** है।

**रिटर्न:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

निर्दिष्ट करता है कि क्या पंजीकृत फ़ॉन्ट्स को समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स पर प्राथमिकता दी जानी चाहिए। जब सक्रिय होता है, तो मिलते-जुलते एम्बेडेड फ़ॉन्ट्स को अस्थायी रूप से संबंधित पंजीकृत फ़ॉन्ट्स से बदल दिया जाता है।

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

डिफ़ॉल्ट **false** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

प्रस्तुति में एम्बेडेड फ़ॉन्ट्स को लौटाता है।

**रिटर्न:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

एम्बेडेड फ़ॉन्ट को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

एम्बेडेड फ़ॉन्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

एम्बेडेड फ़ॉन्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

प्रस्तुति में फ़ॉन्ट बदलें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

प्रस्तुति में फ़ॉन्ट बदलें, जो [FontSubstRule](../../com.aspose.slides/fontsubstrule) में प्रदान की गई जानकारी का उपयोग करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Font substitution info |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

प्रस्तुति में फ़ॉन्ट बदलें, जो [FontSubstRule](../../com.aspose.slides/fontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Font substitution rules collection |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का बाइट एरे प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // प्रस्तुति में उपयोग किए गए सभी फ़ॉन्ट्स प्राप्त करें
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // प्रस्तुति में पहले फ़ॉन्ट की रेगुलर शैली का बाइट एरे प्राप्त करें
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | फ़ॉन्ट डेटा ऑब्जेक्ट जिसमें फ़ॉन्ट [IFontData](../../com.aspose.slides/ifontdata) के बारे में जानकारी है। |
| fontStyle | int | फ़ॉन्ट की वह शैली जिसके लिए डेटा प्राप्त करना है [FontStyleType](../../com.aspose.slides/fontstyletype)। |

**रिटर्न:**
byte[] - निर्दिष्ट फ़ॉन्ट शैली के लिए फ़ॉन्ट डेटा युक्त बाइट एरे। यदि फ़ॉन्ट डेटा या शैली नहीं मिलती है, तो null लौटाता है।

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर का निर्धारण करता है।

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // प्रस्तुति में उपयोग किए गए सभी फ़ॉन्ट्स प्राप्त करें
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // प्रस्तुति में पहले फ़ॉन्ट की रेगुलर शैली का बाइट एरे प्राप्त करें
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
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