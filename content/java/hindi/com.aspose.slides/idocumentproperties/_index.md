---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Represents properties of a presentation.
type: docs
url: /hi/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

एक प्रस्तुतीकरण की गुणधर्मों का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | ऐप संस्करण लौटाता है। |
| [getNameOfApplication()](#getNameOfApplication--) | एप्लिकेशन का नाम लौटाता है या सेट करता है। |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | एप्लिकेशन का नाम लौटाता है या सेट करता है। |
| [getCompany()](#getCompany--) | कंपनी गुण लौटाता है या सेट करता है। |
| [setCompany(String value)](#setCompany-java.lang.String-) | कंपनी गुण लौटाता है या सेट करता है। |
| [getManager()](#getManager--) | प्रबंधक गुण लौटाता है या सेट करता है। |
| [setManager(String value)](#setManager-java.lang.String-) | प्रबंधक गुण लौटाता है या सेट करता है। |
| [getPresentationFormat()](#getPresentationFormat--) | प्रस्तुतीकरण के इच्छित प्रारूप को लौटाता है या सेट करता है। |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | प्रस्तुतीकरण के इच्छित प्रारूप को लौटाता है या सेट करता है। |
| [getSharedDoc()](#getSharedDoc--) | निर्धारित करता है कि प्रस्तुतीकरण कई लोगों के बीच साझा है या नहीं। |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | निर्धारित करता है कि प्रस्तुतीकरण कई लोगों के बीच साझा है या नहीं। |
| [getApplicationTemplate()](#getApplicationTemplate--) | एप्लिकेशन के टेम्प्लेट को लौटाता है या सेट करता है। |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | एप्लिकेशन के टेम्प्लेट को लौटाता है या सेट करता है। |
| [getTotalEditingTime()](#getTotalEditingTime--) | प्रस्तुतीकरण का कुल संपादन समय। |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | प्रस्तुतीकरण का कुल संपादन समय। |
| [getTitle()](#getTitle--) | प्रस्तुतीकरण का शीर्षक लौटाता है या सेट करता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | प्रस्तुतीकरण का शीर्षक लौटाता है या सेट करता है। |
| [getSubject()](#getSubject--) | प्रस्तुतीकरण का विषय लौटाता है या सेट करता है। |
| [setSubject(String value)](#setSubject-java.lang.String-) | प्रस्तुतीकरण का विषय लौटाता है या सेट करता है। |
| [getAuthor()](#getAuthor--) | प्रस्तुतीकरण का लेखक लौटाता है या सेट करता है। |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | प्रस्तुतीकरण का लेखक लौटाता है या सेट करता है। |
| [getKeywords()](#getKeywords--) | प्रस्तुतीकरण के कुंजीशब्द लौटाता है या सेट करता है। |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | प्रस्तुतीकरण के कुंजीशब्द लौटाता है या सेट करता है। |
| [getComments()](#getComments--) | प्रस्तुतीकरण की टिप्पणी लौटाता है या सेट करता है। |
| [setComments(String value)](#setComments-java.lang.String-) | प्रस्तुतीकरण की टिप्पणी लौटाता है या सेट करता है। |
| [getCategory()](#getCategory--) | प्रस्तुतीकरण की श्रेणी लौटाता है या सेट करता है। |
| [setCategory(String value)](#setCategory-java.lang.String-) | प्रस्तुतीकरण की श्रेणी लौटाता है या सेट करता है। |
| [getCreatedTime()](#getCreatedTime--) | प्रस्तुतीकरण के निर्माण की तिथि लौटाता है। |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | प्रस्तुतीकरण के निर्माण की तिथि लौटाता है। |
| [getLastSavedTime()](#getLastSavedTime--) | प्रस्तुतीकरण के अंतिम संशोधन की तिथि लौटाता है। |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | प्रस्तुतीकरण के अंतिम संशोधन की तिथि लौटाता है। |
| [getLastPrinted()](#getLastPrinted--) | अंतिम बार जब प्रस्तुतीकरण मुद्रित हुआ, उसकी तिथि लौटाता है। |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | अंतिम बार जब प्रस्तुतीकरण मुद्रित हुआ, उसकी तिथि लौटाता है। |
| [getLastSavedBy()](#getLastSavedBy--) | अंतिम बार जिसने प्रस्तुतीकरण संशोधित किया, उसका नाम लौटाता है या सेट करता है। |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | अंतिम बार जिसने प्रस्तुतीकरण संशोधित किया, उसका नाम लौटाता है या सेट करता है। |
| [getRevisionNumber()](#getRevisionNumber--) | प्रस्तुतीकरण संशोधन संख्या लौटाता है या सेट करता है। |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | प्रस्तुतीकरण संशोधन संख्या लौटाता है या सेट करता है। |
| [getContentStatus()](#getContentStatus--) | प्रस्तुतीकरण की सामग्री स्थिति लौटाता है या सेट करता है। |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | प्रस्तुतीकरण की सामग्री स्थिति लौटाता है या सेट करता है। |
| [getContentType()](#getContentType--) | प्रस्तुतीकरण की सामग्री प्रकार लौटाता है या सेट करता है। |
| [setContentType(String value)](#setContentType-java.lang.String-) | प्रस्तुतीकरण की सामग्री प्रकार लौटाता है या सेट करता है। |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase दस्तावेज़ गुण लौटाता है या सेट करता है। |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase दस्तावेज़ गुण लौटाता है या सेट करता है। |
| [getScaleCrop()](#getScaleCrop--) | दस्तावेज़ थंबनेल की प्रदर्शन मोड दर्शाता है। |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | दस्तावेज़ थंबनेल की प्रदर्शन मोड दर्शाता है। |
| [getLinksUpToDate()](#getLinksUpToDate--) | संकेत देता है कि दस्तावेज़ में हाइपरलिंक्स अद्यतित हैं या नहीं। |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | संकेत देता है कि दस्तावेज़ में हाइपरलिंक्स अद्यतित हैं या नहीं। |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक्स केवल इस भाग में निर्माता द्वारा अद्यतन किए गए थे। |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक्स केवल इस भाग में निर्माता द्वारा अद्यतन किए गए थे। |
| [getSlides()](#getSlides--) | प्रस्तुतीकरण दस्तावेज़ में कुल स्लाइड की संख्या निर्दिष्ट करता है। |
| [getHiddenSlides()](#getHiddenSlides--) | प्रस्तुतीकरण दस्तावेज़ में छिपे स्लाइड की संख्या निर्दिष्ट करता है। |
| [getNotes()](#getNotes--) | नोट्स वाले प्रस्तुतीकरण में स्लाइड की संख्या निर्दिष्ट करता है। |
| [getParagraphs()](#getParagraphs--) | दस्तावेज़ में पाए गए कुल पैराग्राफ की संख्या (यदि लागू हो) निर्दिष्ट करता है। |
| [getWords()](#getWords--) | दस्तावेज़ में शब्दों की कुल संख्या निर्दिष्ट करता है। |
| [getMultimediaClips()](#getMultimediaClips--) | दस्तावेज़ में मौजूद कुल ध्वनि या वीडियो क्लिप की संख्या निर्दिष्ट करता है। |
| [getTitlesOfParts()](#getTitlesOfParts--) | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। |
| [getHeadingPairs()](#getHeadingPairs--) | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | संग्रह में वास्तव में मौजूद कस्टम गुणों की संख्या लौटाता है। |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | निर्दिष्ट अनुक्रमांक पर कस्टम गुण का नाम लौटाता है। |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | निर्दिष्ट नाम वाले कस्टम गुण को हटाता है। |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | निर्दिष्ट नाम वाले कस्टम गुण की उपस्थिति जांचता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | निर्दिष्ट नाम वाले कस्टम गुण को लौटाता है या सेट करता है। |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट नाम वाले कस्टम गुण को लौटाता है या सेट करता है। |
| [clearCustomProperties()](#clearCustomProperties--) | सभी कस्टम गुणों को हटाता है। |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | सभी builtIn गुणों को साफ़ करता है और डिफ़ॉल्ट मान सेट करता है। |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | कस्टम गुणों से नामित बूलियन मान प्राप्त करता है। |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | कस्टम गुणों से नामित पूर्णांक मान प्राप्त करता है। |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | कस्टम गुणों से नामित DateTime मान प्राप्त करता है। |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | कस्टम गुणों से नामित स्ट्रिंग मान प्राप्त करता है। |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | कस्टम गुणों से नामित फ़्लोट मान प्राप्त करता है। |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | कस्टम गुणों से नामित डबल मान प्राप्त करता है। |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | नामित बूलियन कस्टम गुण सेट करता है। |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | नामित पूर्णांक कस्टम गुण सेट करता है। |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | नामित DateTime कस्टम गुण सेट करता है। |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | नामित स्ट्रिंग कस्टम गुण सेट करता है। |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | नामित फ़्लोट कस्टम गुण सेट करता है। |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | नामित डबल कस्टम गुण सेट करता है। |
| [getSensitivityLabels()](#getSensitivityLabels--) | कस्टम दस्तावेज़ गुणों से संवेदनशीलता लेबल की एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)। |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

ऐप संस्करण लौटाता है। केवल-पढ़ने योग्य String.

--------------------

इस तत्व की सामग्री का रूप XX.YYYY होना चाहिए, जहाँ X और Y संख्यात्मक मान दर्शाते हैं; अन्यथा दस्तावेज़ को गैर-अनुरूप माना जाएगा। Aspose.Slides अपना संस्करण रूप XX.YY.ZZ में दर्शाता है, जहाँ:  
XX – प्रमुख संस्करण  
YY – उप-संस्करण  
ZZ – पैच संस्करण  
उदाहरण के लिए, मान 23.0105 का अर्थ है Aspose.Slides संस्करण 23.1.5।

**रिटर्न:**  
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

एप्लिकेशन का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

एप्लिकेशन का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

कंपनी गुण लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

कंपनी गुण लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

प्रबंधक गुण लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

प्रबंधक गुण लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

प्रस्तुतीकरण के इच्छित प्रारूप को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

प्रस्तुतीकरण के इच्छित प्रारूप को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

निर्धारित करता है कि प्रस्तुतीकरण कई लोगों के बीच साझा है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**  
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

निर्धारित करता है कि प्रस्तुतीकरण कई लोगों के बीच साझा है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

एप्लिकेशन के टेम्प्लेट को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

एप्लिकेशन के टेम्प्लेट को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

प्रस्तुतीकरण का कुल संपादन समय। पढ़ें/लिखें double.

**रिटर्न:**  
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

प्रस्तुतीकरण का कुल संपादन समय। पढ़ें/लिखें double.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

प्रस्तुतीकरण का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

प्रस्तुतीकरण का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

प्रस्तुतीकरण का विषय लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

प्रस्तुतीकरण का विषय लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

प्रस्तुतीकरण का लेखक लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

प्रस्तुतीकरण का लेखक लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

प्रस्तुतीकरण के कुंजीशब्द लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

प्रस्तुतीकरण के कुंजीशब्द लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

प्रस्तुतीकरण की टिप्पणी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

प्रस्तुतीकरण की टिप्पणी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

प्रस्तुतीकरण की श्रेणी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

प्रस्तुतीकरण की श्रेणी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
| मान | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

प्रस्तुति की निर्माण तिथि लौटाता है। मान UTC में हैं। पढ़ें/लिखें java.util.Date.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

प्रस्तुति की निर्माण तिथि सेट करता है। मान UTC में हैं। पढ़ें/लिखें java.util.Date.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

प्रस्तुति की अंतिम संशोधित तिथि लौटाता है। मान UTC में हैं। पढ़ें/लिखें java.util.Date. केवल-पढ़ने योग्य जब Presentation.DocumentProperties का उपयोग किया जाता है (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे DocumentProperties उदाहरण द्वारा बदल सकते हैं जिसे विधि [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाया जाता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) विधि सारांश में उदाहरण देखें।

**Returns:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

प्रस्तुति की अंतिम संशोधित तिथि सेट करता है। मान UTC में हैं। पढ़ें/लिखें java.util.Date. केवल-पढ़ने योग्य जब Presentation.DocumentProperties का उपयोग किया जाता है (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे DocumentProperties उदाहरण द्वारा बदल सकते हैं जिसे विधि [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाया जाता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) विधि सारांश में उदाहरण देखें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

प्रस्तुति के अंतिम प्रिंट होने की तिथि लौटाता है। पढ़ें/लिखें java.util.Date.

**Returns:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

प्रस्तुति के अंतिम प्रिंट होने की तिथि सेट करता है। पढ़ें/लिखें java.util.Date.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Returns:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

प्रस्तुति का संस्करण संख्या लौटाता है या सेट करता है। पढ़ें/लिखें int.

**Returns:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

प्रस्तुति का संस्करण संख्या लौटाता है या सेट करता है। पढ़ें/लिखें int.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

प्रस्तुति की सामग्री स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Returns:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

प्रस्तुति की सामग्री स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

प्रस्तुति का सामग्री प्रकार लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Returns:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

प्रस्तुति का सामग्री प्रकार लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

HyperlinkBase दस्तावेज़ गुण लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Returns:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

HyperlinkBase दस्तावेज़ गुण लौटाता है या सेट करता है। पढ़ें/लिखें String.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। इस तत्व को **true** पर सेट करने से थंबनेल को डिस्प्ले के अनुसार स्केल किया जाता है। इस तत्व को **false** पर सेट करने से थंबनेल को क्रॉप करके केवल डिस्प्ले में फिट होने वाले भाग दिखाए जाते हैं। पढ़ें/लिखें boolean.

**Returns:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। इस तत्व को **true** पर सेट करने से थंबनेल को डिस्प्ले के अनुसार स्केल किया जाता है। इस तत्व को **false** पर सेट करने से थंबनेल को क्रॉप करके केवल डिस्प्ले में फिट होने वाले भाग दिखाए जाते हैं। पढ़ें/लिखें boolean.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

दस्तावेज़ में हाइपरलिंक की अद्यतन स्थिति दर्शाता है। इस तत्व को **true** पर सेट करने से हाइपरलिंक अपडेट होते हैं। इस तत्व को **false** पर सेट करने से हाइपरलिंक पुरानी हो जाती हैं। पढ़ें/लिखें boolean.

**Returns:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

दस्तावेज़ में हाइपरलिंक की अद्यतन स्थिति दर्शाता है। इस तत्व को **true** पर सेट करने से हाइपरलिंक अपडेट होते हैं। इस तत्व को **false** पर सेट करने से हाइपरलिंक पुरानी हो जाती हैं। पढ़ें/लिखें boolean.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

निर्दिष्ट भाग में एक या अधिक हाइपरलिंक को केवल उस भाग द्वारा अपडेट किया गया था। अगला प्रोड्यूसर इस दस्तावेज़ को खोलते समय इस भाग में निर्दिष्ट नए हाइपरलिंक के साथ संबंधों को अपडेट करेगा। पढ़ें/लिखें boolean.

**Returns:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

निर्दिष्ट भाग में एक या अधिक हाइपरलिंक को केवल उस भाग द्वारा अपडेट किया गया था। अगला प्रोड्यूसर इस दस्तावेज़ को खोलते समय इस भाग में निर्दिष्ट नए हाइपरलिंक के साथ संबंधों को अपडेट करेगा। पढ़ें/लिखें boolean.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या दर्शाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या दर्शाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

प्रस्तुति में नोट्स वाली स्लाइडों की संख्या दर्शाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

यदि लागू हो तो दस्तावेज़ में पाए गए कुल पैराग्राफों की संख्या दर्शाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

दस्तावेज़ में कुल शब्दों की संख्या दर्शाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

दस्तावेज़ में मौजूद सभी ध्वनि या वीडियो क्लिप की कुल संख्या दर्शाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

प्रत्येक दस्तावेज़ भाग का शीर्षक दर्शाता है। ये भाग वास्तविक दस्तावेज़ भाग नहीं, बल्कि दस्तावेज़ अनुभागों का अवधारणात्मक प्रतिनिधित्व हैं। केवल-पढ़ने योग्य java.lang.String[].

**Returns:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल-पढ़ने योग्य com.aspose.slides.IHeadingPair[].

**Returns:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

कलेक्शन में वास्तव में मौजूद कस्टम प्रॉपर्टी की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**Returns:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

निर्दिष्ट सूचकांक पर कस्टम प्रॉपर्टी का नाम लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कस्टम प्रॉपर्टी को प्राप्त करने के लिए शून्य-आधारित सूचकांक। |

**Returns:**
java.lang.String - निर्दिष्ट सूचकांक पर कस्टम प्रॉपर्टी नाम.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाई जाने वाली कस्टम प्रॉपर्टी का नाम। |

**Returns:**
boolean - यदि प्रॉपर्टी हटाई गई तो true, अन्यथा false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी की उपस्थिति जांचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | जांचे जाने वाली कस्टम प्रॉपर्टी का नाम। |

**Returns:**
boolean - यदि प्रॉपर्टी मौजूद है तो true, अन्यथा false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

--------------------

मान **int**, **float**, **double**, **String**, **boolean** या **Date** हो सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

--------------------

मान **int**, **float**, **double**, **String**, **boolean** या **Date** हो सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

सभी कस्टम प्रॉपर्टी हटाता है।

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

सभी बिल्ट-इन प्रॉपर्टी साफ करता है और डिफ़ॉल्ट मान सेट करता है।

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

कस्टम प्रॉपर्टी से निर्दिष्ट बूलियन मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | boolean[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

कस्टम प्रॉपर्टी से निर्दिष्ट पूर्णांक मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | int[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

कस्टम प्रॉपर्टी से निर्दिष्ट DateTime मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.util.Date[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

कस्टम प्रॉपर्टी से निर्दिष्ट स्ट्रिंग मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.lang.String[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

कस्टम प्रॉपर्टी से निर्दिष्ट float मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | float[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

कस्टम प्रॉपर्टी से निर्दिष्ट double मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | double[] | कस्टम प्रॉपर्टी मान |
| नाम | java.lang.String | प्रॉपर्टी को प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम। |
| मान | double[] | कस्टम प्रॉपर्टी का मान |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

नामित boolean कस्टम प्रॉपर्टी को सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | boolean | कस्टम प्रॉपर्टी का मान |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

नामित int कस्टम प्रॉपर्टी को सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | int | कस्टम प्रॉपर्टी का मान |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

नामित DateTime कस्टम प्रॉपर्टी को सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.util.Date | कस्टम प्रॉपर्टी का मान |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

नामित string कस्टम प्रॉपर्टी को सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.lang.String | कस्टम प्रॉपर्टी का मान |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

नामित float कस्टम प्रॉपर्टी को सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | float | कस्टम प्रॉपर्टी का मान |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

नामित double कस्टम प्रॉपर्टी को सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | double | कस्टम प्रॉपर्टी का मान |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

कस्टम दस्तावेज़ प्रॉपर्टीज़ से सेंसिटिविटी लेबल्स की एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)।

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