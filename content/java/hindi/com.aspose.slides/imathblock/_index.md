---
title: IMathBlock
second_title: Aspose.Slides for Java API संदर्भ
description: MathParagraph के अंदर मौजूद गणितीय पाठ का एक उदाहरण निर्दिष्ट करता है और यह अपनी स्वयं की पंक्ति पर शुरू होता है।
type: docs
url: /hi/com.aspose.slides/imathblock/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | सेपरेटर कैरेक्टर के साथ सभी चाइल्ड एलिमेंट्स को सीमांकित करता है (ब्रैकेट्स के बिना) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | इस ब्लॉक के चाइल्ड एलिमेंट्स को निर्धारित कैरेक्टर्स (जैसे कोष्ठक या अन्य) में फ्रेमिंग के रूप में घेरता है और सेपरेटर कैरेक्टर के साथ सीमांकित करता है |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | इस ब्लॉक को किसी अन्य गणितीय ब्लॉक के साथ जोड़ता है |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | इस [IMathBlock](../../com.aspose.slides/imathblock) की सामग्री को MathML के रूप में सहेजता है |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

सेपरेटर कैरेक्टर के साथ सभी चाइल्ड एलिमेंट्स को सीमांकित करता है (ब्रैकेट्स के बिना)

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
| separatorCharacter | char | सेपरेटर के रूप में उपयोग किया जाने वाला कैरेक्टर |

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter एलिमेंट का इंस्टेंस
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

इस ब्लॉक के चाइल्ड एलिमेंट्स को निर्धारित कैरेक्टर्स (जैसे कोष्ठक या अन्य) में फ्रेमिंग के रूप में घेरता है और सेपरेटर कैरेक्टर के साथ सीमांकित करता है

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
| beginningCharacter | char | आरंभिक कैरेक्टर (आमतौर पर बायाँ ब्रैकेट) |
| endingCharacter | char | समाप्ति कैरेक्टर (आमतौर पर दायाँ ब्रैकेट) |
| separatorCharacter | char | सेपरेटर कैरेक्टर |

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - प्रकार [IMathDelimiter](../../com.aspose.slides/imathdelimiter) का गणितीय एलिमेंट जिसमें निर्दिष्ट कैरेक्टर्स फ्रेमिंग और डिलिमीटर के रूप में शामिल हैं
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

इस ब्लॉक को किसी अन्य गणितीय ब्लॉक के साथ जोड़ता है

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | जॉइनिंग ब्लॉक |

**रिटर्न:**  
[IMathBlock](../../com.aspose.slides/imathblock) - इस गणितीय ब्लॉक को जोड़ने के बाद
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

इस [IMathBlock](../../com.aspose.slides/imathblock) की सामग्री को MathML के रूप में सहेजता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |