---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /hi/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

एक प्रस्तुति के गुणों का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | ऐप संस्करण को लौटाता है। |
| [getNameOfApplication()](#getNameOfApplication--) | एप्लीकेशन का नाम लौटाता है या सेट करता है। |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | एप्लीकेशन का नाम लौटाता है या सेट करता है। |
| [getCompany()](#getCompany--) | कंपनी गुण को लौटाता है या सेट करता है। |
| [setCompany(String value)](#setCompany-java.lang.String-) | कंपनी गुण को लौटाता है या सेट करता है। |
| [getManager()](#getManager--) | प्रबंधक गुण को लौटाता है या सेट करता है। |
| [setManager(String value)](#setManager-java.lang.String-) | प्रबंधक गुण को लौटाता है या सेट करता है। |
| [getPresentationFormat()](#getPresentationFormat--) | प्रस्तुति के इच्छित स्वरूप को लौटाता है या सेट करता है। |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | प्रस्तुति के इच्छित स्वरूप को लौटाता है या सेट करता है। |
| [getSharedDoc()](#getSharedDoc--) | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा की गई है या नहीं। |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा की गई है या नहीं। |
| [getApplicationTemplate()](#getApplicationTemplate--) | एप्लीकेशन का टेम्पलेट लौटाता है या सेट करता है। |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | एप्लीकेशन का टेम्पलेट लौटाता है या सेट करता है। |
| [getTotalEditingTime()](#getTotalEditingTime--) | एक प्रस्तुति का कुल संपादन समय। |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | एक प्रस्तुति का कुल संपादन समय। |
| [getTitle()](#getTitle--) | प्रस्तुति का शीर्षक लौटाता है या सेट करता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | प्रस्तुति का शीर्षक लौटाता है या सेट करता है। |
| [getSubject()](#getSubject--) | प्रस्तुति का विषय लौटाता है या सेट करता है। |
| [setSubject(String value)](#setSubject-java.lang.String-) | प्रस्तुति का विषय लौटाता है या सेट करता है। |
| [getAuthor()](#getAuthor--) | प्रस्तुति के लेखक को लौटाता है या सेट करता है। |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | प्रस्तुति के लेखक को लौटाता है या सेट करता है। |
| [getKeywords()](#getKeywords--) | प्रस्तुति के कुंजीशब्दों को लौटाता है या सेट करता है। |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | प्रस्तुति के कुंजीशब्दों को लौटाता है या सेट करता है। |
| [getComments()](#getComments--) | प्रस्तुति की टिप्पणियों को लौटाता है या सेट करता है। |
| [setComments(String value)](#setComments-java.lang.String-) | प्रस्तुति की टिप्पणियों को लौटाता है या सेट करता है। |
| [getCategory()](#getCategory--) | प्रस्तुति की श्रेणी को लौटाता है या सेट करता है। |
| [setCategory(String value)](#setCategory-java.lang.String-) | प्रस्तुति की श्रेणी को लौटाता है या सेट करता है। |
| [getCreatedTime()](#getCreatedTime--) | प्रस्तुति के बनाए जाने की तिथि को लौटाता है। |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | प्रस्तुति के बनाए जाने की तिथि को लौटाता है। |
| [getLastSavedTime()](#getLastSavedTime--) | प्रस्तुति के अंतिम संशोधित होने की तिथि को लौटाता है। |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | प्रस्तुति के अंतिम संशोधित होने की तिथि को लौटाता है। |
| [getLastPrinted()](#getLastPrinted--) | प्रस्तुति के अंतिम बार मुद्रित होने की तिथि को लौटाता है। |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | प्रस्तुति के अंतिम बार मुद्रित होने की तिथि को लौटाता है। |
| [getLastSavedBy()](#getLastSavedBy--) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। |
| [getRevisionNumber()](#getRevisionNumber--) | प्रस्तुति का संशोधन क्रमांक लौटाता है या सेट करता है। |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | प्रस्तुति का संशोधन क्रमांक लौटाता है या सेट करता है। |
| [getContentStatus()](#getContentStatus--) | प्रस्तुति की सामग्री स्थिति को लौटाता है या सेट करता है। |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | प्रस्तुति की सामग्री स्थिति को लौटाता है या सेट करता है। |
| [getContentType()](#getContentType--) | प्रस्तुति के सामग्री प्रकार को लौटाता है या सेट करता है। |
| [setContentType(String value)](#setContentType-java.lang.String-) | प्रस्तुति के सामग्री प्रकार को लौटाता है या सेट करता है। |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase दस्तावेज़ गुण को लौटाता है या सेट करता है। |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase दस्तावेज़ गुण को लौटाता है या सेट करता है। |
| [getScaleCrop()](#getScaleCrop--) | दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। |
| [getLinksUpToDate()](#getLinksUpToDate--) | दस्तावेज़ में हाइपरलिंक अद्यतन हैं या नहीं को दर्शाता है। |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | दस्तावेज़ में हाइपरलिंक अद्यतन हैं या नहीं को दर्शाता है। |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में ही निर्माता द्वारा अपडेट किए गए थे। |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में ही निर्माता द्वारा अपडेट किए गए थे। |
| [getSlides()](#getSlides--) | प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या निर्दिष्ट करता है। |
| [getHiddenSlides()](#getHiddenSlides--) | प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या निर्दिष्ट करता है। |
| [getNotes()](#getNotes--) | प्रस्तुति में नोट्स वाले स्लाइडों की संख्या निर्दिष्ट करता है। |
| [getParagraphs()](#getParagraphs--) | यदि लागू हो तो दस्तावेज़ में पाए गए कुल पैराग्राफों की संख्या निर्दिष्ट करता है। |
| [getWords()](#getWords--) | दस्तावेज़ में शामिल कुल शब्दों की संख्या निर्दिष्ट करता है। |
| [getMultimediaClips()](#getMultimediaClips--) | दस्तावेज़ में उपस्थित ध्वनि या वीडियो क्लिप्स की कुल संख्या निर्दिष्ट करता है। |
| [getTitlesOfParts()](#getTitlesOfParts--) | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। |
| [getHeadingPairs()](#getHeadingPairs--) | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | कलेक्शन में वास्तव में मौजूद कस्टम गुणों की संख्या लौटाता है। |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | निर्दिष्ट अनुक्रमांक पर एक कस्टम गुण का नाम लौटाता है। |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | निर्दिष्ट नाम से जुड़े कस्टम गुण को हटाता है। |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | निर्दिष्ट नाम वाले कस्टम गुण की उपस्थिति जांचता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | निर्दिष्ट नाम से जुड़े कस्टम गुण को लौटाता है या सेट करता है। |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट नाम से जुड़े कस्टम गुण को लौटाता है या सेट करता है। |
| [clearCustomProperties()](#clearCustomProperties--) | सभी कस्टम गुणों को हटाता है। |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | सभी builtIn गुणों को साफ़ करता है और डिफ़ॉल्ट मान सेट करता है। |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sets a named boolean custom property. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sets a named integer custom property. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sets a named DateTime custom property. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sets a named string custom property. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sets a named float custom property. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sets a named double custom property. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

ऐप संस्करण को लौटाता है। केवल पढ़ने योग्य String.

--------------------

इस तत्व की सामग्री का स्वरूप XX.YYYY होना चाहिए, जहाँ X और Y संख्यात्मक मान दर्शाते हैं; अन्यथा दस्तावेज़ को गैर-अनुरूप माना जाएगा। Aspose.Slides अपना संस्करण स्वरूप XX.YY.ZZ में दर्शाता है, जहाँ: XX - प्रमुख संस्करण YY - गौण संस्करण ZZ - पैच संस्करण उदाहरण के लिए, मान 23.0105 का अर्थ है Aspose.Slides संस्करण 23.1.5।

**रिटर्न:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

एप्लीकेशन का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

एप्लीकेशन का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

कंपनी गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

कंपनी गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

प्रबंधक गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

प्रबंधक गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

प्रस्तुति के इच्छित स्वरूप को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

प्रस्तुति के इच्छित स्वरूप को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा की गई है या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा की गई है या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

एप्लीकेशन का टेम्पलेट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

एप्लीकेशन का टेम्पलेट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

एक प्रस्तुति का कुल संपादन समय। पढ़ने/लिखने योग्य double।

**रिटर्न:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

एक प्रस्तुति का कुल संपादन समय। पढ़ने/लिखने योग्य double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

प्रस्तुति का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

प्रस्तुति का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

प्रस्तुति का विषय लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

प्रस्तुति का विषय लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

प्रस्तुति के लेखक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

प्रस्तुति के लेखक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

प्रस्तुति के कुंजीशब्दों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

प्रस्तुति के कुंजीशब्दों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

प्रस्तुति की टिप्पणियों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

प्रस्तुति की टिप्पणियों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

प्रस्तुति की श्रेणी को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

प्रस्तुति की श्रेणी को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

प्रस्तुति के बनाए जाने की तिथि को लौटाता है। मान UTC में होते हैं। पढ़ने/लिखने योग्य java.util.Date।

**रिटर्न:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

प्रस्तुति के बनाए जाने की तिथि को लौटाता है। मान UTC में होते हैं। पढ़ने/लिखने योग्य java.util.Date।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

प्रस्तुति के अंतिम संशोधित होने की तिथि को लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल पढ़ने योग्य (क्योंकि इसे IPresentation ऑब्जेक्ट सहेजे जाने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट किया जाता है)। इसे [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाए गए DocumentProperties इंस्टैंस से बदला जा सकता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) मेथड सारांश में उदाहरण देखें।

**रिटर्न:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

प्रस्तुति के अंतिम संशोधित होने की तिथि को लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल पढ़ने योग्य (क्योंकि इसे IPresentation ऑब्जेक्ट सहेजे जाने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट किया जाता है)। इसे [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाए गए DocumentProperties इंस्टैंस से बदला जा सकता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) मेथड सारांश में उदाहरण देखें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

प्रस्तुति के अंतिम बार मुद्रित होने की तिथि को लौटाता है। पढ़ने/लिखने योग्य java.util.Date।

**रिटर्न:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

प्रस्तुति के अंतिम बार मुद्रित होने की तिथि को लौटाता है। पढ़ने/लिखने योग्य java.util.Date।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

प्रस्तुति का संशोधन क्रमांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

प्रस्तुति का संशोधन क्रमांक लौटा

त है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

प्रस्तुति की सामग्री स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

प्रस्तुति की सामग्री स्थिति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```




```

प्रस्तुति के सामग्री प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

प्रस्तुति के सामग्री प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

HyperlinkBase दस्तावेज़ गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

HyperlinkBase दस्तावेज़ गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। इस तत्व को **true** सेट करने से दस्तावेज़ थंबनेल को डिस्प्ले पर स्केल करने की अनुमति मिलती है। इस तत्व को **false** सेट करने से केवल उन भागों को दिखाने के लिए थंबनेल को क्रॉप किया जाता है जो डिस्प्ले में फिट होते हैं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। इस तत्व को **true** सेट करने से दस्तावेज़ थंबनेल को डिस्प्ले पर स्केल करने की अनुमति मिलती है। इस तत्व को **false** सेट करने से केवल उन भागों को दिखाने के लिए थंबनेल को क्रॉप किया जाता है जो डिस्प्ले में फिट होते हैं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

दस्तावेज़ में हाइपरलिंक अद्यतन हैं या नहीं को दर्शाता है। इस तत्व को **true** सेट करने से संकेत मिलता है कि हाइपरलिंक अपडेटेड हैं। इस तत्व को **false** सेट करने से संकेत मिलता है कि हाइपरलिंक पुराने हैं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

दस्तावेज़ में हाइपरलिंक अद्यतन हैं या नहीं को दर्शाता है। इस तत्व को **true** सेट करने से संकेत मिलता है कि हाइपरलिंक अपडेटेड हैं। इस तत्व को **false** सेट करने से संकेत मिलता है कि हाइपरलिंक पुराने हैं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में ही निर्माता द्वारा अपडेट किए गए थे। अगला निर्माता इस दस्तावेज़ को खोलते समय नए हाइपरलिंक के साथ संबंध अपडेट करेगा। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में ही निर्माता द्वारा अपडेट किए गए थे। अगला निर्माता इस दस्तावेज़ को खोलते समय नए हाइपरलिंक के साथ संबंध अपडेट करेगा। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

छिपी स्लाइडों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

नोट्स वाले स्लाइडों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

यदि लागू हो तो दस्तावेज़ में पाए गए कुल पैराग्राफों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

दस्तावेज़ में शामिल कुल शब्दों की संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

दस्तावेज़ में उपस्थित ध्वनि या वीडियो क्लिप्स की कुल संख्या निर्दिष्ट करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग वास्तविक दस्तावेज़ भाग नहीं, बल्कि अनुभागों का अवधारणात्मक प्रतिनिधित्व हैं। केवल पढ़ने योग्य String[]।

**रिटर्न:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल पढ़ने योग्य IHeadingPair[]।

**रिटर्न:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

कलेक्शन में वास्तव में मौजूद कस्टम गुणों की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

निर्दिष्ट अनुक्रमांक पर एक कस्टम गुण का नाम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कस्टम गुण को प्राप्त करने का शून्य-आधारित अनुक्रमांक। |

**रिटर्न:**
java.lang.String - निर्दिष्ट अनुक्रमांक पर कस्टम गुण नाम।

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

निर्दिष्ट नाम से जुड़े कस्टम गुण को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए कस्टम गुण का नाम। |

**रिटर्न:**
boolean - यदि गुण हटाया गया तो true, अन्यथा false।

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

निर्दिष्ट नाम वाले कस्टम गुण की उपस्थिति जांचता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | जांचने के लिए कस्टम गुण का नाम। |

**रिटर्न:**
boolean - यदि गुण मौजूद है तो true, अन्यथा false।

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

निर्दिष्ट नाम से जुड़े कस्टम गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Object।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**रिटर्न:**
java.lang.Object

--------------------

मान **int**, **float**, **double**, **String**, **boolean** या **Date** हो सकता है।

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

निर्दिष्ट नाम से जुड़े कस्टम गुण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Object।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

सभी कस्टम गुणों को हटाता है।

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

सभी builtIn गुणों को साफ़ करता है और डिफ़ॉल्ट मान सेट करता है।

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

एक नामित boolean मान को कस्टम गुणों से प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने वाले कस्टम गुण का नाम |
| value | boolean[] | कस्टम गुण मान |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

एक नामित integer मान को कस्टम गुणों से प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने वाले कस्टम गुण का नाम |
| value | int[] | कस्टम गुण मान |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

एक नामित DateTime मान को कस्टम गुणों से प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने वाले कस्टम गुण का नाम |
| value | java.util.Date[] | कस्टम गुण मान |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

एक नामित string मान को कस्टम गुणों से प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने वाले कस्टम गुण का नाम |
| value | java.lang.String[] | कस्टम गुण मान |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

एक नामित float मान को कस्टम गुणों से प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने वाले कस्टम गुण का नाम |
| value | float[] | कस्टम गुण मान |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

एक नामित double मान को कस्टम गुणों से प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने वाले कस्टम गुण का नाम |
| value | double[] | कस्टम गुण मान |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

एक नामित boolean कस्टम गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने वाले कस्टम गुण का नाम |
| value | boolean | कस्टम गुण मान |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

एक नामित integer कस्टम गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने वाले कस्टम गुण का नाम |
| value | int | कस्टम गुण मान |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```




```

एक नामित DateTime कस्टम गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने वाले कस्टम गुण का नाम |
| value | java.util.Date | कस्टम गुण मान |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

एक नामित string कस्टम गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने वाले कस्टम गुण का नाम |
| value | java.lang.String | कस्टम गुण मान |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

एक नामित float कस्टम गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने वाले कस्टम गुण का नाम |
| value | float | कस्टम गुण मान |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

एक नामित double कस्टम गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने वाले कस्टम गुण का नाम |
| value | double | कस्टम गुण मान |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

कस्टम दस्तावेज़ गुणों से संवेदनशीलता लेबल्स की एक array प्राप्त करता है (Microsoft Information Protection SDK Metadata)।

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
com.aspose.slides.ISensitivityLabel[]