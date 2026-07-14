---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: डिजिटल हस्ताक्षर वाली फ़ाइल।
type: docs
url: /hi/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

डिजिटल हस्ताक्षर वाली फ़ाइल।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCertificate()](#getCertificate--) | वह प्रमाणपत्र ऑब्जेक्ट जो दस्तावेज़ पर हस्ताक्षर करने के लिए उपयोग किया गया था। |
| [isValid()](#isValid--) | यदि यह डिजिटल हस्ताक्षर मान्य है और दस्तावेज़ में कोई छेड़छाड़ नहीं हुई है, तो यह मान true होगा। |
| [getSignTime()](#getSignTime--) | वह समय जब दस्तावेज़ पर हस्ताक्षर किया गया था। |
| [getComments()](#getComments--) | हस्ताक्षर का उद्देश्य। |
| [setComments(String value)](#setComments-java.lang.String-) | हस्ताक्षर का उद्देश्य। |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

प्रलेख पर हस्ताक्षर करने के लिए उपयोग किया गया प्रमाणपत्र ऑब्जेक्ट। केवल पढ़ने योग्य byte[].

**रिटर्न:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

यदि यह डिजिटल हस्ताक्षर मान्य है और दस्तावेज़ में कोई छेड़छाड़ नहीं हुई है, तो यह मान true होगा। केवल पढ़ने योग्य boolean.

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

**रिटर्न:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

दस्तावेज़ पर हस्ताक्षर किए जाने का समय। केवल पढ़ने योग्य java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

हस्ताक्षर का उद्देश्य। पढ़ने/लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

हस्ताक्षर का उद्देश्य। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |