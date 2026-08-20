---
title: BlobManagementOptions
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: विकल्प प्रस्तुत करता है जो BLOB हैंडलिंग नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग किए जा सकते हैं।
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

BLOB हैंडलिंग नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग की जा सकने वाली विकल्पों का प्रतिनिधित्व करता है।

## निर्माणकर्ता

| निर्माणकर्ता | वर्णन |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | नए डिफ़ॉल्ट blob प्रबंधन विकल्प बनाता है। |

## विधियां

| विधि | वर्णन |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | यह गुण यह परिभाषित करता है कि Presentation क्लास का एक उदाहरण स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, उदाहरण के जीवनकाल के दौरान। |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | यह गुण यह परिभाषित करता है कि Presentation क्लास का एक उदाहरण स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, उदाहरण के जीवनकाल के दौरान। |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | यह गुण यह परिभाषित करता है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग उल्लेखनीय रूप से घटता है, लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है। |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | यह गुण यह परिभाषित करता है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग उल्लेखनीय रूप से घटता है, लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है। |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | वह रूट पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | वह रूट पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | वह अधिकतम कुल आकार (बाइट्स में) निर्धारित करता है जिसे सभी BLOBs मेमोरी में ले सकते हैं। |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | वह अधिकतम कुल आकार (बाइट्स में) निर्धारित करता है जिसे सभी BLOBs मेमोरी में ले सकते हैं। |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

नए डिफ़ॉल्ट blob प्रबंधन विकल्प बनाता है।

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

यह गुण यह परिभाषित करता है कि Presentation क्लास का एक उदाहरण स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, उदाहरण के जीवनकाल के दौरान। यदि उदाहरण मालिक है, तो वह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन में सुधार करता है, लेकिन Presentation के उदाहरण के जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) बदला नहीं जा सकता।

**रिटर्न:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

यह गुण यह परिभाषित करता है कि Presentation क्लास का एक उदाहरण स्रोत-फ़ाइल या स्ट्रीम का मालिक हो सकता है या नहीं, उदाहरण के जीवनकाल के दौरान। यदि उदाहरण मालिक है, तो वह स्रोत को लॉक करता है। यह BLOBs के साथ काम करते समय मेमोरी उपयोग और प्रदर्शन में सुधार करता है, लेकिन Presentation के उदाहरण के जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) बदला नहीं जा सकता।

**पैरामीटर:**  
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

यह गुण यह परिभाषित करता है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग उल्लेखनीय रूप से घटता है, लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है।

--------------------

सभी फ़ाइलें प्रस्तुति के साथ कार्य समाप्त होने के बाद हटा दी जाएँगी।

**रिटर्न:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

यह गुण यह परिभाषित करता है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जिससे मेमोरी उपयोग उल्लेखनीय रूप से घटता है, लेकिन फ़ाइलें बनाने के लिए अनुमतियों की आवश्यकता होती है।

--------------------

सभी फ़ाइलें प्रस्तुति के साथ कार्य समाप्त होने के बाद हटा दी जाएँगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

वह रूट पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। डिफ़ॉल्ट रूप से सिस्टम अस्थायी निर्देशिका उपयोग की जाएगी। होस्टिंग प्रोसेस के पास वहाँ फ़ाइलें और फोल्डर बनाने की अनुमति होनी चाहिए।

**रिटर्न:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

वह रूट पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। डिफ़ॉल्ट रूप से सिस्टम अस्थायी निर्देशिका उपयोग की जाएगी। होस्टिंग प्रोसेस के पास वहाँ फ़ाइलें और फोल्डर बनाने की अनुमति होनी चाहिए।

**पैरामीटर:**  
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

सभी BLOBs द्वारा मेमोरी में घेरे जा सकने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs को मेमोरी में लोड किया जाता है; केवल जब यह सीमा पहुँचती है, तब वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है, परन्तु इससे उच्च मेमोरी उपयोग हो सकता है। अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए इस गुण का उपयोग करें।

--------------------

यह गुण तब अनदेखा किया जाता है जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि उस स्थिति में मेमोरी ही एकल भंडारण स्थान होती है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई असर नहीं रहता।

--------------------

डिफ़ॉल्ट मान 629,145,600 बाइट्स (600 MB) है।

--------------------

आप इस गुण को शून्य पर भी सेट कर सकते हैं, लेकिन फिर भी एक छोटा न्यूनतम मेमोरी मात्रा आरक्षित होगी।

**रिटर्न:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

सभी BLOBs द्वारा मेमोरी में घेरे जा सकने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs को मेमोरी में लोड किया जाता है; केवल जब यह सीमा पहुँचती है, तब वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग में लाए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है, परन्तु इससे उच्च मेमोरी उपयोग हो सकता है। अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए इस गुण का उपयोग करें।

--------------------

यह गुण तब अनदेखा किया जाता है जब \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) को false पर सेट किया जाता है, क्योंकि उस स्थिति में मेमोरी ही एकल भंडारण स्थान होती है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई असर नहीं रहता।

--------------------

डिफ़ॉल्ट मान 629,145,600 बाइट्स (600 MB) है।

--------------------

आप इस गुण को शून्य पर भी सेट कर सकते हैं, लेकिन फिर भी एक छोटा न्यूनतम मेमोरी मात्रा आरक्षित होगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | long |  |