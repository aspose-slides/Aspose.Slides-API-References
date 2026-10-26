---
title: IMathBlock
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक गणितीय पाठ का उदाहरण निर्दिष्ट करता है जो MathParagraph के भीतर अंतर्भुक्त है और अपनी अलग पंक्ति पर शुरू होता है।
type: docs
url: /hi/com.aspose.slides/imathblock/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

एक गणितीय पाठ का उदाहरण निर्धारित करता है जो MathParagraph के भीतर स्थित होता है और अपनी अलग पंक्ति पर शुरू होता है। सभी गणितीय क्षेत्रों, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों की श्रेणियाँ, और सूत्र शामिल हैं, को गणित ब्लॉक द्वारा प्रतिनिधित्व किया जाता है।

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | सेपरेटर अक्षर (कोष्ठकों के बिना) के साथ सभी उप-तत्वों को सीमांकित करता है |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | इस ब्लॉक के उप-तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य फ्रेमिंग के रूप में संलग्न करता है और सेपरेटर अक्षर के साथ सीमांकित करता है |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | एक अन्य गणितीय ब्लॉक को इस के साथ जोड़ता है |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | इस [IMathBlock](../../com.aspose.slides/imathblock) की सामग्री को MathML के रूप में सहेजता है |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

सेपरेटर अक्षर (कोष्ठकों के बिना) के साथ सभी उप-तत्वों को सीमांकित करता है

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char | सेपरेटर के रूप में प्रयुक्त अक्षर |

**रिटर्न:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter तत्व का उदाहरण
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

इस ब्लॉक के उप-तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य फ्रेमिंग के रूप में संलग्न करता है और सेपरेटर अक्षर के साथ सीमांकित करता है

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारंभिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |
| separatorCharacter | char | सेपरेटर अक्षर |

**रिटर्न:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) प्रकार का गणितीय तत्व जो निर्दिष्ट अक्षरों को फ्रेमिंग और सीमा के रूप में शामिल करता है
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

एक अन्य गणितीय ब्लॉक को इस के साथ जोड़ता है

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | जोड़ने वाला ब्लॉक |

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - जुड़ने के बाद यह गणितीय ब्लॉक
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

इस [IMathBlock](../../com.aspose.slides/imathblock) की सामग्री को MathML के रूप में सहेजता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्षित स्ट्रीम |