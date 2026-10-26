---
title: License
second_title: Aspose.Slides for Java API संदर्भ
description: घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/license/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)  
```
public final class License implements ILicense
```

घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।

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
## कंस्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) | इस क्लास का एक नया उदाहरण आरंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस करता है। |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस करता है। |
| [getVersion()](#getVersion--) | Aspose.Slides for Java का संस्करण लौटाता है। |
| [resetLicense()](#resetLicense--) | लाइसेंस रीसेट करें। |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


इस क्लास का एक नया उदाहरण आरंभ करता है।

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


घटक को लाइसेंस करता है।

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


**परामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | लाइसेंस-समाहित स्ट्रीम। मूल्यांकन मोड में स्विच करने के लिए null सेट करें। |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


घटक को लाइसेंस करता है।

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

**परामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| namePath | java.lang.String | पूर्ण या संक्षिप्त फ़ाइल-नाम या एम्बेडेड रिसोर्स का नाम। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग उपयोग करें। |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Aspose.Slides for Java का संस्करण लौटाता है।

**वापसी:**  
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


लाइसेंस रीसेट करें। घटक में लाइसेंस रीसेट करने के लिए इस मेथड का उपयोग करें।

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


जाँचें कि क्या लाइसेंस घटक पर लागू है।

**वापसी:**  
boolean