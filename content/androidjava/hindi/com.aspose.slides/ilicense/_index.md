---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Provides methods to license the component.
type: docs
url: /hi/com.aspose.slides/ilicense/
---```
public interface ILicense
```

घटक को लाइसेंस करने के लिए विधियां प्रदान करता है।

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | घटक को लाइसेंस करता है। |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस करता है। |
| [resetLicense()](#resetLicense--) | लाइसेंस को रीसेट करें |
| [isLicensed()](#isLicensed--) | जांचें कि लाइसेंस घटक पर लागू है या नहीं |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


घटक को लाइसेंस करता है।

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseName | java.lang.String | एक पूर्ण या छोटा फ़ाइल नाम या एन्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें।

--------------------

निम्नलिखित स्थानों में लाइसेंस खोजने का प्रयास करता है:

1. स्पष्ट पथ।
2. घटक असेंबली का फ़ोल्डर।
3. क्लाइंट की कॉलिंग असेंबली का फ़ोल्डर।
4. एंट्री असेंबली का फ़ोल्डर।
5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स। |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


घटक को लाइसेंस करता है।

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | एक स्ट्रीम जिसमें लाइसेंस हो।

--------------------

इस मेथड का उपयोग एक स्ट्रीम से लाइसेंस लोड करने के लिए करें। |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


लाइसेंस को रीसेट करें

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

इस मेथड का उपयोग घटक में लाइसेंस रीसेट करने के लिए करें।

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


जाँचें कि लाइसेंस घटक पर लागू है या नहीं

**रिटर्न मान:**
boolean - true यदि घटक लाइसेंस किया गया है, अन्यथा false