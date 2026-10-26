---
title: BlobManagementOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: BLOB हैंडलिंग नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/blobmanagementoptions/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

BLOB प्रबंधन नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | नई डिफ़ॉल्ट ब्लॉब प्रबंधन विकल्प बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | यह प्रॉपर्टी निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस जीवनकाल के दौरान स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं। |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | यह प्रॉपर्टी निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस जीवनकाल के दौरान स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं। |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | यह प्रॉपर्टी निर्धारित करती है कि ब्लॉब्स के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग काफी घटता है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है। |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | यह प्रॉपर्टी निर्धारित करती है कि ब्लॉब्स के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग काफी घटता है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है। |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | वह मूल पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | वह मूल पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | सभी ब्लॉब्स द्वारा मेमोरी में घेरे जाने वाले कुल अधिकतम आकार (बाइट में) को परिभाषित करता है। |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | सभी ब्लॉब्स द्वारा मेमोरी में घेरे जाने वाले कुल अधिकतम आकार (बाइट में) को परिभाषित करता है। |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

नई डिफ़ॉल्ट ब्लॉब प्रबंधन विकल्प बनाता है।

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

यह प्रॉपर्टी निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस जीवनकाल के दौरान स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह ब्लॉब्स के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को बेहतर बनाता है, लेकिन Presentation के इंस्टेंस जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) को बदला नहीं जा सकता।

**रिटर्न:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

यह प्रॉपर्टी निर्धारित करती है कि Presentation क्लास का एक इंस्टेंस जीवनकाल के दौरान स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं। यदि इंस्टेंस मालिक है, तो यह स्रोत को लॉक करता है। यह ब्लॉब्स के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन को बेहतर बनाता है, लेकिन Presentation के इंस्टेंस जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) को बदला नहीं जा सकता।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

यह प्रॉपर्टी निर्धारित करती है कि ब्लॉब्स के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग काफी घटता है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है।

--------------------

प्रेजेंटेशन के साथ काम समाप्त होने के बाद सभी फ़ाइलें हटा दी जाएँगी।

**रिटर्न:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

यह प्रॉपर्टी निर्धारित करती है कि ब्लॉब्स के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग काफी घटता है लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है।

--------------------

प्रेजेंटेशन के साथ काम समाप्त होने के बाद सभी फ़ाइलें हटा दी जाएँगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

अस्थायी फ़ाइलों के निर्माण के लिए मूल पथ। डिफ़ॉल्ट रूप से सिस्टम का अस्थायी निर्देशिका उपयोग की जाएगी। होस्टिंग प्रोसेस को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए।

**रिटर्न:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

अस्थायी फ़ाइलों के निर्माण के लिए मूल पथ। डिफ़ॉल्ट रूप में सिस्टम का अस्थायी निर्देशिका उपयोग की जाएगी। होस्टिंग प्रोसेस को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

सभी ब्लॉब्स द्वारा मेमोरी में घेरे जाने वाले कुल अधिकतम आकार (बाइट में) को परिभाषित करता है। डिफ़ॉल्ट रूप से, सभी ब्लॉब्स मेमोरी में लोड होते हैं; केवल जब यह सीमा पहुँच जाए तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाए जाते हैं। मेमोरी में ब्लॉब्स रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। इस प्रॉपर्टी का उपयोग अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को समायोजित करने के लिए करें।

--------------------

यह प्रॉपर्टी तब नहीं मानी जाती जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि तब मेमोरी ही एकमात्र संग्रह स्थान होती है और इन-मेमोरी ब्लॉब उपयोग को सीमित करने का कोई प्रभाव नहीं रहता।

--------------------

डिफ़ॉल्ट मान 629,145,600 बाइट (600 MB) है।

--------------------

आप इस प्रॉपर्टी को शून्य पर सेट कर सकते हैं, लेकिन फिर भी एक छोटी न्यूनतम मात्रा में मेमोरी आरक्षित रहनी चाहिए।

**रिटर्न:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

सभी ब्लॉब्स द्वारा मेमोरी में घेरे जाने वाले कुल अधिकतम आकार (बाइट में) को परिभाषित करता है। डिफ़ॉल्ट रूप से, सभी ब्लॉब्स मेमोरी में लोड होते हैं; केवल जब यह सीमा पहुँच जाए तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाए जाते हैं। मेमोरी में ब्लॉब्स रखना प्रदर्शन को अधिकतम करता है लेकिन उच्च मेमोरी उपयोग का कारण बन सकता है। इस प्रॉपर्टी का उपयोग अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को समायोजित करने के लिए करें।

--------------------

यह प्रॉपर्टी तब नहीं मानी जाती जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि तब मेमोरी ही एकमात्र संग्रह स्थान होती है और इन-मेमोरी ब्लॉब उपयोग को सीमित करने का कोई प्रभाव नहीं रहता।

--------------------

डिफ़ॉल्ट मान 629,145,600 बाइट (600 MB) है।

--------------------

आप इस प्रॉपर्टी को शून्य पर सेट कर सकते हैं, लेकिन फिर भी एक छोटी न्यूनतम मात्रा में मेमोरी आरक्षित रहनी चाहिए।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |