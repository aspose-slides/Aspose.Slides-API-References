---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक बाइनरी लार्ज ऑब्जेक्ट BLOB एक बाइनरी डेटा है जो एकल इकाई के रूप में संग्रहीत होता है - i.e.
type: docs
url: /hi/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

एक बाइनरी लार्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एकल इकाई के रूप में संग्रहीत होता है - i.e. BLOB ऑडियो, वीडियो या प्रस्तुति स्वयं हो सकता है। BLOBs के साथ काम करते समय मेमोरी खपत को अनुकूलित करने के लिए कई तकनीकों का उपयोग किया जाता है - जो पहले से प्रस्तुति में संग्रहीत था या बाद में प्रोग्रामmatically जोड़ी जा सकती हैं। [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) का उपयोग करके आप [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस जीवनकाल के दौरान BLOBs हैंडलिंग से संबंधित विभिन्न व्यवहार पहलुओं को बदल सकते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | यह प्रॉपर्टी यह निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | यह प्रॉपर्टी यह निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | यह प्रॉपर्टी यह निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जो मेमोरी खपत को काफी कम करती है लेकिन फ़ाइलें बनाते समय अनुमति की आवश्यकता होती है। |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | यह प्रॉपर्टी यह निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जो मेमोरी खपत को काफी कम करती है लेकिन फ़ाइलें बनाते समय अनुमति की आवश्यकता होती है। |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | अस्थायी फ़ाइलें जहाँ बनाई जाएँगी, उसका मूल पथ। |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | अस्थायी फ़ाइलें जहाँ बनाई जाएँगी, उसका मूल पथ। |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | सभी BLOBs द्वारा मेमोरी में घेरने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | सभी BLOBs द्वारा मेमोरी में घेरने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

यह प्रॉपर्टी यह निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन को बेहतर बनाने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को Presentation के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:

--------------------
> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException फेंकी जाएगी क्योंकि pres.pptx को Presentation जीवनकाल के लिए लॉक किया गया है
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation ऑब्जेक्ट नष्ट होने के बाद, फ़ाइल अनलॉक हो जाती है और उसे हटाया जा सकता है
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**वापसी:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

यह प्रॉपर्टी यह निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस स्रोत - फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन को बेहतर बनाने में मदद करता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) को Presentation के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है:

--------------------
> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException फेंकी जाएगी क्योंकि pres.pptx को Presentation जीवनकाल के लिए लॉक किया गया है
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation ऑब्जेक्ट नष्ट होने के बाद, फ़ाइल अनलॉक हो जाती है और उसे हटाया जा सकता है
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

यह प्रॉपर्टी यह निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जो मेमोरी खपत को काफी कम करती है लेकिन फ़ाइलें बनाते समय अनुमति की आवश्यकता होती है।

--------------------
प्रस्तुति के साथ कार्य समाप्त होने के बाद सभी फ़ाइलें हटा दी जाएँगी।

**वापसी:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

यह प्रॉपर्टी यह निर्धारित करती है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जो मेमोरी खपत को काफी कम करती है लेकिन फ़ाइलें बनाते समय अनुमति की आवश्यकता होती है।

--------------------
प्रस्तुति के साथ कार्य समाप्त होने के बाद सभी फ़ाइलें हटा दी जाएँगी।

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

अस्थायी फ़ाइलें जहाँ बनाई जाएँगी, उसका मूल पथ। सिस्टम का अस्थायी निर्देशिका डिफ़ॉल्ट रूप में उपयोग किया जाएगा। होस्टिंग प्रक्रिया को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए।

**वापसी:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

अस्थायी फ़ाइलें जहाँ बनाई जाएँगी, उसका मूल पथ। सिस्टम का अस्थायी निर्देशिका डिफ़ॉल्ट रूप में उपयोग किया जाएगा। होस्टिंग प्रक्रिया को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए।

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

सभी BLOBs द्वारा मेमोरी में घेरने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। डिफ़ॉल्ट रूप में, सभी BLOBs मेमोरी में लोड होते हैं; केवल जब यह सीमा प्राप्त हो जाती है तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग किए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है लेकिन इससे उच्च मेमोरी उपयोग हो सकता है। इस प्रॉपर्टी का उपयोग करके आप अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित कर सकते हैं।

--------------------
यह प्रॉपर्टी तब अनदेखी की जाएगी जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि तब मेमोरी ही एकमात्र उपलब्ध स्टोरेज स्थान होती है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई प्रभाव नहीं रहता।

--------------------
डिफ़ॉल्ट मान 629,145,600 बाइट्स (600 MB) है।

--------------------
आप इस प्रॉपर्टी को शून्य पर सेट कर सकते हैं, लेकिन फिर भी एक छोटा न्यूनतम मेमोरी मात्रा आरक्षित रह जाएगी।

**वापसी:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

सभी BLOBs द्वारा मेमोरी में घेरने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। डिफ़ॉल्ट रूप में, सभी BLOBs मेमोरी में लोड होते हैं; केवल जब यह सीमा प्राप्त हो जाती है तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग किए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है लेकिन इससे उच्च मेमोरी उपयोग हो सकता है। इस प्रॉपर्टी का उपयोग करके आप अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित कर सकते हैं।

--------------------
यह प्रॉपर्टी तब अनदेखी की जाएगी जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि तब मेमोरी ही एकमात्र उपलब्ध स्टोरेज स्थान होती है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई प्रभाव नहीं रहता।

--------------------
डिफ़ॉल्ट मान 629,145,600 बाइट्स (600 MB) है।

--------------------
आप इस प्रॉपर्टी को शून्य पर सेट कर सकते हैं, लेकिन फिर भी एक छोटा न्यूनतम मेमोरी मात्रा आरक्षित रह जाएगी।

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | long |  |