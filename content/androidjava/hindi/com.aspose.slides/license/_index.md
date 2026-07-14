---
title: License
second_title: Java API रेफ़रेंस द्वारा Aspose.Slides for Android
description: घटक को लाइसेंस करने के लिए विधियां प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/license/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

घटक को लाइसेंस करने के लिए विधियां प्रदान करता है।

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## Constructors

| निर्माता | विवरण |
| --- | --- |
| [License()](#License--) | इस वर्ग का एक नया उदाहरण आरंभ करता है। |
## Methods

| विधि | विवरण |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस देता है। |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस देता है। |
| [getVersion()](#getVersion--) | Aspose.Slides for Android का संस्करण Java के माध्यम से लौटाता है। |
| [resetLicense()](#resetLicense--) | लाइसेंस रीसेट करें। |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

इस वर्ग का एक नया उदाहरण आरंभ करता है।

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

घटक को लाइसेंस देता है।

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | लाइसेंस युक्त एक स्ट्रीम। मूल्यांकन मोड में स्विच करने के लिए null का उपयोग करें। |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

घटक को लाइसेंस देता है।

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| namePath | java.lang.String | पूर्ण या संक्षिप्त फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें। |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Aspose.Slides for Android का संस्करण Java के माध्यम से लौटाता है।

**रिटर्न:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

लाइसेंस रीसेट करें। घटक में लाइसेंस को रीसेट करने के लिए इस विधि का उपयोग करें।

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

जाँचें कि लाइसेंस घटक पर लागू है या नहीं

**रिटर्न:**
boolean