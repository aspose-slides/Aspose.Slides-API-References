---
title: DigitalSignature
second_title: Aspose.Slides जावा API रेफ़रेंस
description: हस्ताक्षरित फ़ाइल में डिजिटल हस्ताक्षर।
type: docs
url: /hi/com.aspose.slides/digitalsignature/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

हस्ताक्षरित फ़ाइल में डिजिटल हस्ताक्षर।

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Presentation इंस्टेंस को प्रारंभ करें
>  Presentation pres = new Presentation();
>  try {
>     // PFX फ़ाइल और PFX पासवर्ड के साथ DigitalSignature ऑब्जेक्ट बनाएं
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // नए डिजिटल हस्ताक्षर में टिप्पणी सेट करें
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Presentation में डिजिटल हस्ताक्षर जोड़ें
>      pres.getDigitalSignatures().add(signature);
>      // Presentation सहेजें
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Presentation इंस्टेंस को प्रारंभ करें
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // सभी डिजिटल हस्ताक्षर वैध हैं या नहीं जांचें
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Creates a new DigitalSignature object with the specified certificate file path and password. |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate object that was used to sign the document. |
| [isValid()](#isValid--) | If this digital signature is valid and the document has not been tampered with, this value will be true. |
| [getSignTime()](#getSignTime--) | The time when the document was signed. |
| [getComments()](#getComments--) | The purpose of signature. |
| [setComments(String value)](#setComments-java.lang.String-) | The purpose of signature. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


निर्दिष्ट प्रमाणपत्र के साथ नया DigitalSignature ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certData | byte[] | प्रमाणपत्र शामिल करने वाला बाइट एरे |
| password | java.lang.String | प्रमाणपत्र तक पहुँचने के लिए आवश्यक पासवर्ड। |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


निर्दिष्ट प्रमाणपत्र फ़ाइल पथ और पासवर्ड के साथ नया DigitalSignature ऑब्जेक्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | प्रमाणपत्र वाली फ़ाइल का पथ। |
| password | java.lang.String | प्रमाणपत्र तक पहुँचने के लिए आवश्यक पासवर्ड। |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


दस्तावेज़ पर हस्ताक्षर करने के लिए उपयोग किया गया प्रमाणपत्र ऑब्जेक्ट। केवल-पढ़ने योग्य byte[]।

**वापसी:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


यदि यह डिजिटल हस्ताक्षर मान्य है और दस्तावेज़ में छेड़छाड़ नहीं की गई है, तो यह मान true होगा। केवल-पढ़ने योग्य boolean।

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:** boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


दस्तावेज़ पर हस्ताक्षर किया गया समय। केवल-पढ़ने योग्य java.util.Date।

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:** java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


हस्ताक्षर का उद्देश्य। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


हस्ताक्षर का उद्देश्य। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |