---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: Digital signature in signed file.
type: docs
url: /hi/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

हस्ताक्षरित फ़ाइल में डिजिटल हस्ताक्षर।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCertificate()](#getCertificate--) | प्रलेख को हस्ताक्षर करने के लिए उपयोग किया गया Certificate ऑब्जेक्ट। |
| [isValid()](#isValid--) | यदि यह डिजिटल हस्ताक्षर मान्य है और प्रलेख में छेड़छाड़ नहीं की गई है, तो यह मान true होगा। |
| [getSignTime()](#getSignTime--) | प्रलेख के हस्ताक्षर किए जाने का समय। |
| [getComments()](#getComments--) | हस्ताक्षर का उद्देश्य। |
| [setComments(String value)](#setComments-java.lang.String-) | हस्ताक्षर का उद्देश्य। |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Certificate object that was used to sign the document. केवल पढ़ने योग्य byte[].

**रिटर्न:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

यदि यह डिजिटल हस्ताक्षर मान्य है और प्रलेख में छेड़छाड़ नहीं की गई है, तो यह मान true होगा। केवल पढ़ने योग्य boolean.

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

प्रलेख के हस्ताक्षर किए जाने का समय। केवल पढ़ने योग्य java.util.Date.

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