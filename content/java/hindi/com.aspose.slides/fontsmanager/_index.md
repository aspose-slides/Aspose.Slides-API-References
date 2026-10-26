---
title: FontsManager
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रस्तुति में फ़ॉन्ट्स का प्रबंधन करता है।
type: docs
url: /hi/com.aspose.slides/fontsmanager/
---
**विरासत:**  
java.lang.Object

**सभी कार्यान्वित इंटरफेस:**  
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)  
```
public class FontsManager implements IFontsManager
```

प्रस्तुति में फ़ॉन्ट्स का प्रबंधन करता है।

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // प्रस्तुति लोड करें
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // प्रतिस्थापित करने के लिए स्रोत फ़ॉन्ट लोड करें
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
>      // प्रस्तुति सहेजें
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | रेंडरिंग के दौरान उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन। |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | रेंडरिंग के दौरान उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन। |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | फ़ॉन्ट फॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन के लिए फ़ॉन्ट संग्रहों का प्रबंधन करने वाले FontFallBack नियमों के उपयोगकर्ता के संग्रह का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | फ़ॉन्ट फॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन के लिए फ़ॉन्ट संग्रहों का प्रबंधन करने वाले FontFallBack नियमों के उपयोगकर्ता के संग्रह का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | प्रस्तुति में उपयोग किए गए फ़ॉन्ट्स को लौटाता है। |
| [getSubstitutions()](#getSubstitutions--) | प्रस्तुति के रेंडरिंग पर प्रतिस्थापित होने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान प्रतिस्थापित किए जाने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | प्रस्तुति में एम्बेड किए गए फ़ॉन्ट्स को लौटाता है। |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | एम्बेड किया गया फ़ॉन्ट हटाता है। |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | एम्बेड किया गया फ़ॉन्ट जोड़ता है। |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | एम्बेड किया गया फ़ॉन्ट जोड़ता है। |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | प्रस्तुति में फ़ॉन्ट को बदलें। |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) में प्रदान की गई जानकारी का उपयोग करके प्रस्तुति में फ़ॉन्ट को बदलें। |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग करके प्रस्तुति में फ़ॉन्ट को बदलें। |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाला बाइट ऐरे प्राप्त करता है। |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | दिए गए बाइट ऐरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर को निर्धारित करता है। |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

रेंडरिंग के दौरान उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन। पढ़ें/लिखें [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**वापसी:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

रेंडरिंग के दौरान उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन। पढ़ें/लिखें [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

फ़ॉन्ट फॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन के लिए फ़ॉन्ट संग्रहों का प्रबंधन करने वाले FontFallBack नियमों के उपयोगकर्ता के संग्रह का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager से खाली या पूर्व-आरम्भ किए गए नियम संग्रह को प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // या 
>      // नियम संग्रह की नई इंस्टेंस का प्रारम्भ करना
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // और FontsManager में मौजूदा संग्रह को नई संग्रह से बदलना 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

फ़ॉन्ट फॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन के लिए फ़ॉन्ट संग्रहों का प्रबंधन करने वाले FontFallBack नियमों के उपयोगकर्ता के संग्रह का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager से खाली या पूर्व-आरम्भ किए गए नियम संग्रह को प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // या 
>      // नियम संग्रह की नई इंस्टेंस का प्रारम्भ करना
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // संग्रह में नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // और FontsManager में मौजूदा संग्रह को नई संग्रह से बदलना 
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

**वापसी:**
com.aspose.slides.IFontData[] - फ़ॉन्ट्स का एरे

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

प्रस्तुति के रेंडरिंग पर प्रतिस्थापित होने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है।

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

**वापसी:**
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
| slides | int[] | उन स्लाइड इंडेक्स की एरे जिनके लिए फ़ॉन्ट प्रतिस्थापन जानकारी प्राप्त करनी है, 1 से शुरू। |

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - निर्दिष्ट स्लाइड्स के लिए सभी फ़ॉन्ट प्रतिस्थापन ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) का संग्रह।

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

प्रस्तुति में एम्बेड किए गए फ़ॉन्ट्स को लौटाता है।

**वापसी:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

एम्बेड किया गया फ़ॉन्ट हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

एम्बेड किया गया फ़ॉन्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

एम्बेड किया गया फ़ॉन्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

प्रस्तुति में फ़ॉन्ट को बदलें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | स्रोत फ़ॉन्ट |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | गंतव्य फ़ॉन्ट |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) में प्रदान की गई जानकारी का उपयोग करके प्रस्तुति में फ़ॉन्ट को बदलें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | फ़ॉन्ट प्रतिस्थापन जानकारी |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग करके प्रस्तुति में फ़ॉन्ट को बदलें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | फ़ॉन्ट प्रतिस्थापन नियम संग्रह |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाला बाइट ऐरे प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // प्रस्तुति में उपयोग किए गए सभी फ़ॉन्ट्स को प्राप्त करें
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // प्रस्तुति में पहले फ़ॉन्ट की नियमित शैली का प्रतिनिधित्व करने वाला बाइट ऐरे प्राप्त करें
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | फ़ॉन्ट डेटा ऑब्जेक्ट जिसमें फ़ॉन्ट [IFontData](../../com.aspose.slides/ifontdata) की जानकारी होती है। |
| fontStyle | int | फ़ॉन्ट शैली जिसके लिए डेटा प्राप्त किया जाता है [FontStyleType](../../com.aspose.slides/fontstyletype)। |

**वापसी:**
byte[] - निर्दिष्ट फ़ॉन्ट शैली के लिए फ़ॉन्ट डेटा वाला बाइट ऐरे। यदि फ़ॉन्ट डेटा या शैली नहीं मिली, तो null लौटाता है।

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

दिये गए बाइट ऐरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर को निर्धारित करता है।

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // प्रस्तुति में उपयोग किए गए सभी फ़ॉन्ट्स को प्राप्त करें
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // प्रस्तुति में पहले फ़ॉन्ट की नियमित शैली का प्रतिनिधित्व करने वाला बाइट ऐरे प्राप्त करें
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // फ़ॉन्ट का एम्बेडिंग स्तर निर्धारित करें
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontBytes | byte[] | फ़ॉन्ट डेटा वाला बाइट ऐरे। |
| fontName | java.lang.String | फ़ॉन्ट का नाम। |

**वापसी:**
int - निर्दिष्ट फ़ॉन्ट का एम्बेडिंग स्तर।