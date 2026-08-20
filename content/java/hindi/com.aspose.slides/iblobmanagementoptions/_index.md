---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API संदर्भ
description: एक बाइनरी बड़े आकार का ऑब्जेक्ट BLOB एक बाइनरी डेटा है जो एक एकल इकाई के रूप में संग्रहीत होता है - i.e.
type: docs
url: /hi/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

एक बाइनरी बड़े आकार का ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक एकल इकाई के रूप में संग्रहीत होता है - i.e. BLOB ऑडियो, वीडियो या प्रस्तुति स्वयं हो सकता है। कई तकनीकों का उपयोग BLOBs के साथ काम करते समय मेमोरी खपत को अनुकूलित करने के लिए किया जाता है - जो पहले से ही प्रस्तुति में संग्रहीत हो चुका है या बाद में प्रोग्रामेटिक रूप से जोड़ा जा सकता है। [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) का उपयोग करके आप [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के जीवनकाल के दौरान BLOBs हैंडलिंग से संबंधित विभिन्न व्यवहार पहलुओं को बदल सकते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

यह प्रॉपर्टी निर्धारित करता है कि क्या Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक बन सकता है इंस्टेंस के जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन को सुधारने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को Presentation के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException फेंका जाएगा क्योंकि pres.pptx को Presentation के जीवनकाल के लिए लॉक किया गया है
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation ऑब्जेक्ट नष्ट होने के बाद, फ़ाइल अनलॉक हो जाती है और इसे हटाया जा सकता है
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
```

**रिटर्न:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

यह प्रॉपर्टी निर्धारित करता है कि क्या Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक बन सकता है इंस्टेंस के जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन को सुधारने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को Presentation के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException फेंका जाएगा क्योंकि pres.pptx को Presentation के जीवनकाल के लिए लॉक किया गया है
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation ऑब्जेक्ट नष्ट होने के बाद, फ़ाइल अनलॉक हो जाती है और इसे हटाया जा सकता है
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

यह प्रॉपर्टी निर्धारित करता है कि क्या अस्थायी फ़ाइलें BLOBs के साथ काम करते समय बनाई जा सकती हैं, जो मेमोरी खपत को काफी कम करता है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है।

--------------------

सभी फ़ाइलें प्रस्तुति के साथ कार्य समाप्त होने के बाद हटा दी जाएँगी।

**रिटर्न:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

यह प्रॉपर्टी निर्धारित करता है कि क्या अस्थायी फ़ाइलें BLOBs के साथ काम करते समय बनाई जा सकती हैं, जो मेमोरी खपत को काफी कम करता है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है।

--------------------

सभी फ़ाइलें प्रस्तुति के साथ कार्य समाप्त होने के बाद हटा दी जाएँगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

अस्थायी फ़ाइलों के निर्माण के लिए मूल पथ। डिफ़ॉल्ट रूप से सिस्टम अस्थायी निर्देशिका उपयोग की जाएगी। होस्टिंग प्रक्रिया को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए।

**रिटर्न:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

अस्थायी फ़ाइलों के निर्माण के लिए मूल पथ। डिफ़ॉल्ट रूप से सिस्टम अस्थायी निर्देशिका उपयोग की जाएगी। होस्टिंग प्रक्रिया को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

सभी BLOBs द्वारा मेमोरी में व्याप्त कुल अधिकतम आकार (बाइट्स में) निर्धारित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँचती है तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाए जाते हैं। BLOBs को मेमोरी में रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए इस प्रॉपर्टी का उपयोग करें।

--------------------

यह प्रॉपर्टी तब अनदेखी की जाती है जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि उस स्थिति में मेमोरी ही एकमात्र स्टोरेज स्थान होती है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई प्रभाव नहीं होता।

--------------------

डिफ़ॉल्ट मान 629,145,600 बाइट्स (600 MB) है।

--------------------

आप इस प्रॉपर्टी को शून्य पर सेट कर सकते हैं, लेकिन फिर भी एक छोटा न्यूनतम मेमोरी मात्रा आरक्षित रहेगी।

**रिटर्न:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

सभी BLOBs द्वारा मेमोरी में व्याप्त कुल अधिकतम आकार (बाइट्स में) निर्धारित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँचती है तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाए जाते हैं। BLOBs को मेमोरी में रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए इस प्रॉपर्टी का उपयोग करें।

--------------------

यह प्रॉपर्टी तब अनदेखी की जाती है जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि उस स्थिति में मेमोरी ही एकमात्र स्टोरेज स्थान होती है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई प्रभाव नहीं होता।

--------------------

डिफ़ॉल्ट मान 629,145,600 बाइट्स (600 MB) है।

--------------------

आप इस प्रॉपर्टी को शून्य पर सेट कर सकते हैं, लेकिन फिर भी एक छोटा न्यूनतम मेमोरी मात्रा आरक्षित रहेगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |