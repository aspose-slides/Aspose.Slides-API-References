---
title: ILicense
second_title: Aspose.Slides for Java API संदर्भ
description: घटक को लाइसेंस करने के लिये विधियाँ प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/ilicense/
---```
public interface ILicense
```

घटक को लाइसेंस करने के लिये विधियाँ प्रदान करता है।

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
| [resetLicense()](#resetLicense--) | लाइसेंस रीसेट करें |
| [isLicensed()](#isLicensed--) | जाँचें कि लाइसेंस घटक पर लागू है या नहीं |
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
| licenseName | java.lang.String | पूरा या छोटा फ़ाइल नाम या एम्बेडेड संसाधन का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिये खाली स्ट्रिंग का उपयोग करें। |

--------------------

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।
2. घटक असेंबली का फ़ोल्डर।
3. क्लाइंट की कॉलिंग असेंबली का फ़ोल्डर।
4. एंट्री असेंबली का फ़ोल्डर।
5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड संसाधन। |

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
| stream | java.io.InputStream | एक स्ट्रिम जो लाइसेंस रखती है। |

--------------------

स्ट्रीम से लाइसेंस लोड करने के लिये इस विधि का इस्तेमाल करें। |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

लाइसेंस रीसेट करें

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

घटक में लाइसेंस रीसेट करने के लिये इस विधि का प्रयोग करें

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

जाँचें कि लाइसेंस घटक पर लागू है या नहीं

**वापसी मान:**
boolean - true यदि घटक लाइसेंस किया गया है, अन्यथा false