---
title: DocumentProperties
second_title: Aspose.Slides जावा API संदर्भ
description: प्रस्तुति के गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/documentproperties/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफेसेस:**  
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable  
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

एक प्रस्तुति की प्रॉपर्टीज़ को दर्शाता है।

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // प्रस्तुति को दर्शाने वाली Presentation क्लास का इंस्टेंस बनाएं
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // प्रस्तुति से जुड़े IDocumentProperties ऑब्जेक्ट का रेफ़रेंस बनाएं
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // बिल्ट-इन गुण प्रदर्शित करें
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // प्रस्तुति को दर्शाने वाली Presentation क्लास का इंस्टेंस बनाएं
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // प्रस्तुति से जुड़े IDocumentProperties ऑब्जेक्ट का रेफ़रेंस बनाएं
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // बिल्ट-इन गुण सेट करें
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // अपनी प्रस्तुति को फ़ाइल में सेव करें
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | क्लास [DocumentProperties](../../com.aspose.slides/documentproperties) का नया इंस्टेंस प्रारम्भ करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | ऐप संस्करण को लौटाता है। |
| [getNameOfApplication()](#getNameOfApplication--) | एप्लिकेशन का नाम प्राप्त करता है या सेट करता है। |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | एप्लिकेशन का नाम प्राप्त करता है या सेट करता है। |
| [getCompany()](#getCompany--) | कंपनी प्रॉपर्टी को प्राप्त या सेट करता है। |
| [setCompany(String value)](#setCompany-java.lang.String-) | कंपनी प्रॉपर्टी को प्राप्त या सेट करता है। |
| [getManager()](#getManager--) | मैनेजर प्रॉपर्टी को प्राप्त या सेट करता है। |
| [setManager(String value)](#setManager-java.lang.String-) | मैनेजर प्रॉपर्टी को प्राप्त या सेट करता है। |
| [getPresentationFormat()](#getPresentationFormat--) | प्रस्तुति के लक्षित फॉर्मेट को प्राप्त या सेट करता है। |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | प्रस्तुति के लक्षित फॉर्मेट को प्राप्त या सेट करता है। |
| [getSharedDoc()](#getSharedDoc--) | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। |
| [getApplicationTemplate()](#getApplicationTemplate--) | एक एप्लिकेशन का टेम्पलेट प्राप्त या सेट करता है। |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | एक एप्लिकेशन का टेम्पलेट प्राप्त या सेट करता है। |
| [getTotalEditingTime()](#getTotalEditingTime--) | प्रस्तुति का कुल संपादन समय। |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | प्रस्तुति का कुल संपादन समय। |
| [getTitle()](#getTitle--) | प्रस्तुति का शीर्षक प्राप्त या सेट करता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | प्रस्तुति का शीर्षक प्राप्त या सेट करता है। |
| [getSubject()](#getSubject--) | प्रस्तुति का विषय प्राप्त या सेट करता है। |
| [setSubject(String value)](#setSubject-java.lang.String-) | प्रस्तुति का विषय प्राप्त या सेट करता है। |
| [getAuthor()](#getAuthor--) | प्रस्तुति के लेखक को प्राप्त या सेट करता है। |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | प्रस्तुति के लेखक को प्राप्त या सेट करता है। |
| [getKeywords()](#getKeywords--) | प्रस्तुति के कुंजीशब्द प्राप्त या सेट करता है। |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | प्रस्तुति के कुंजीशब्द प्राप्त या सेट करता है। |
| [getComments()](#getComments--) | प्रस्तुति की टिप्पणी प्राप्त या सेट करता है। |
| [setComments(String value)](#setComments-java.lang.String-) | प्रस्तुति की टिप्पणी प्राप्त या सेट करता है। |
| [getCategory()](#getCategory--) | प्रस्तुति की श्रेणी प्राप्त या सेट करता है। |
| [setCategory(String value)](#setCategory-java.lang.String-) | प्रस्तुति की श्रेणी प्राप्त या सेट करता है। |
| [getCreatedTime()](#getCreatedTime--) | प्रस्तुति बनाने की तिथि लौटाता है। |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | प्रस्तुति बनाने की तिथि लौटाता है। |
| [getLastSavedTime()](#getLastSavedTime--) | प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। |
| [getLastPrinted()](#getLastPrinted--) | प्रस्तुति के अंतिम प्रिंट की तिथि लौटाता है। |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | प्रस्तुति के अंतिम प्रिंट की तिथि लौटाता है। |
| [getLastSavedBy()](#getLastSavedBy--) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम प्राप्त या सेट करता है। |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम प्राप्त या सेट करता है। |
| [getRevisionNumber()](#getRevisionNumber--) | प्रस्तुति संस्करण संख्या प्राप्त या सेट करता है। |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | प्रस्तुति संस्करण संख्या प्राप्त या सेट करता है। |
| [getContentStatus()](#getContentStatus--) | प्रस्तुति की सामग्री स्थिति प्राप्त या सेट करता है। |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | प्रस्तुति की सामग्री स्थिति प्राप्त या सेट करता है। |
| [getContentType()](#getContentType--) | प्रस्तुति के सामग्री प्रकार को प्राप्त या सेट करता है। |
| [setContentType(String value)](#setContentType-java.lang.String-) | प्रस्तुति के सामग्री प्रकार को प्राप्त या सेट करता है। |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase दस्तावेज़ प्रॉपर्टी प्राप्त या सेट करता है। |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase दस्तावेज़ प्रॉपर्टी प्राप्त या सेट करता है। |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | कलेक्शन में वास्तव में मौजूद कस्टम प्रॉपर्टीज़ की संख्या लौटाता है। |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | निर्दिष्ट इंडेक्स पर कस्टम प्रॉपर्टी का नाम लौटाता है। |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को हटाता है। |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी की उपस्थिति जांचता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को प्राप्त या सेट करता है। |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को प्राप्त या सेट करता है। |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | नामित बूलियन कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | नामित इंटीजर कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | नामित DateTime कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | नामित स्ट्रिंग कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | नामित फ़्लोट कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | नामित डबल कस्टम प्रॉपर्टी सेट करता है। |
| [clearCustomProperties()](#clearCustomProperties--) | सभी कस्टम प्रॉपर्टीज़ को हटाता है। |
| [getSensitivityLabels()](#getSensitivityLabels--) | कस्टम दस्तावेज़ प्रॉपर्टीज़ से संवेदनशीलता लेबल की एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | सभी builtIn प्रॉपर्टीज़ के लिए डिफ़ॉल्ट मान साफ़ और सेट करता है। |
| [getScaleCrop()](#getScaleCrop--) | दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | दस्तावेज़ थंबनेल के प्रदर्शन मोड को दर्शाता है। |
| [getLinksUpToDate()](#getLinksUpToDate--) | दस्तावेज़ में हाइपरलिंक्स अद्यतन हैं या नहीं दर्शाता है। |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | दस्तावेज़ में हाइपरलिंक्स अद्यतन हैं या नहीं दर्शाता है। |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक्स केवल इस भाग द्वारा निर्माता द्वारा अपडेट किए गए थे। |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक्स केवल इस भाग द्वारा निर्माता द्वारा अपडेट किए गए थे। |
| [getSlides()](#getSlides--) | एक प्रस्तुति दस्तावेज़ में कुल स्लाइड्स की संख्या लौटाता है। |
| [getHiddenSlides()](#getHiddenSlides--) | प्रस्तुति दस्तावेज़ में छिपी हुई स्लाइड्स की संख्या लौटाता है। |
| [getNotes()](#getNotes--) | नोट्स सहित स्लाइड्स की संख्या लौटाता है। |
| [getParagraphs()](#getParagraphs--) | यदि लागू हो तो दस्तावेज़ में पाए गए कुल पैराग्राफ की संख्या लौटाता है। |
| [getWords()](#getWords--) | दस्तावेज़ में मौजूद कुल शब्दों की संख्या लौटाता है। |
| [getMultimediaClips()](#getMultimediaClips--) | दस्तावेज़ में मौजूद ध्वनि या वीडियो क्लिप की कुल संख्या लौटाता है। |
| [getTitlesOfParts()](#getTitlesOfParts--) | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। |
| [getHeadingPairs()](#getHeadingPairs--) | दस्तावेज़ भागों के समूह और प्रत्येक समूह में भागों की संख्या को दर्शाता है। |
| [deepClone()](#deepClone--) | वर्तमान ऑब्जेक्ट की क्लोन बनाता है। |
| [cloneT()](#cloneT--) | वर्तमान ऑब्जेक्ट की क्लोन बनाता है। |

### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

क्लास [DocumentProperties](../../com.aspose.slides/documentproperties) का नया इंस्टेंस प्रारम्भ करता है।

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

ऐप संस्करण को लौटाता है। केवल-पढ़ने योग्य String.

**वापसी:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

एप्लिकेशन का नाम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

एप्लिकेशन का नाम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

कंपनी प्रॉपर्टी को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

कंपनी प्रॉपर्टी को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

मैनेजर प्रॉपर्टी को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

मैनेजर प्रॉपर्टी को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

प्रस्तुति के लक्षित फॉर्मेट को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

प्रस्तुति के लक्षित फॉर्मेट को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ने/लिखने योग्य boolean.

**वापसी:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ने/लिखने योग्य boolean.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

एक एप्लिकेशन का टेम्पलेट प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

एक एप्लिकेशन का टेम्पलेट प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

प्रस्तुति का कुल संपादन समय। पढ़ने/लिखने योग्य double.

**वापसी:**  
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

प्रस्तुति का कुल संपादन समय। पढ़ने/लिखने योग्य double.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

प्रस्तुति का शीर्षक प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

प्रस्तुति का शीर्षक प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

प्रस्तुति का विषय प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

प्रस्तुति का विषय प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

प्रस्तुति के लेखक को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

प्रस्तुति के लेखक को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

प्रस्तुति के कुंजीशब्द प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

प्रस्तुति के कुंजीशब्द प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

प्रस्तुति की टिप्पणी प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

प्रस्तुति की टिप्पणी प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

प्रस्तुति की श्रेणी प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

प्रस्तुति की श्रेणी प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
प्रस्तुति के निर्माण की तिथि लौटाता है। मान UTC में हैं। पढ़ें/लिखें java.util.Date.

**वापसी:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

प्रस्तुति के निर्माण की तिथि लौटाता है। मान UTC में हैं। पढ़ें/लिखें java.util.Date.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे विधि [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाए गए DocumentProperties इंस्टेंस के माध्यम से बदला जा सकता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) विधि सारांश में उदाहरण देखें।

**वापसी:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

प्रस्तुति के अंतिम संशोधन की तिथि लौटाता है। मान UTC में हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट होगा)। इसे विधि [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाए गए DocumentProperties इंस्टेंस के माध्यम से बदला जा सकता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) विधि सारांश में उदाहरण देखें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

प्रस्तुति को अंतिम बार प्रिंट किए जाने की तिथि लौटाता है। पढ़ें/लिखें java.util.Date.

**वापसी:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

प्रस्तुति को अंतिम बार प्रिंट किए जाने की तिथि लौटाता है। पढ़ें/लिखें java.util.Date.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

प्रस्तुति का रिवीजन नंबर लौटाता है या सेट करता है। पढ़ें/लिखें int.

**वापसी:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

प्रस्तुति का रिवीजन नंबर लौटाता है या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

प्रस्तुति की कंटेंट स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

प्रस्तुति की कंटेंट स्थिति लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

प्रस्तुति का कंटेंट प्रकार लौटाता है या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

प्रस्तुति का कंटेंट प्रकार लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

HyperlinkBase दस्तावेज़ प्रॉपर्टी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

HyperlinkBase दस्तावेज़ प्रॉपर्टी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

कस्टम प्रॉपर्टीज़ की वास्तविक संख्या लौटाता है जो संग्रह में मौजूद हैं। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

निर्दिष्ट इंडेक्‍स पर कस्टम प्रॉपर्टी का नाम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कस्टम प्रॉपर्टी को प्राप्त करने के लिए शून्य-आधारित इंडेक्स। |

**वापसी:**
java.lang.String - निर्दिष्ट इंडेक्स पर कस्टम प्रॉपर्टी का नाम।
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए कस्टम प्रॉपर्टी का नाम। |

**वापसी:**
boolean - यदि प्रॉपर्टी हटाई गई तो true, अन्यथा false।
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

निर्दिष्ट नाम वाली कस्टम प्रॉपर्टी के अस्तित्व की जाँच करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | जाँचने के लिए कस्टम प्रॉपर्टी का नाम। |

**वापसी:**
boolean - यदि प्रॉपर्टी मौजूद है तो true, अन्यथा false।
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

निर्दिष्ट नाम से जुड़े कस्टम प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

--------------------

मान हो सकता है **int**, **float**, **String**, **boolean** या **Date**.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**वापसी:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

निर्दिष्ट नाम से जुड़े कस्टम प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

--------------------

मान हो सकता है **int**, **float**, **String**, **boolean** या **Date**.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

कस्टम प्रॉपर्टीज़ से नामांकित boolean मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | boolean[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

कस्टम प्रॉपर्टीज़ से नामांकित integer मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | int[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

कस्टम प्रॉपर्टीज़ से नामांकित DateTime मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.util.Date[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

कस्टम प्रॉपर्टीज़ से नामांकित स्ट्रिंग मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.lang.String[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

कस्टम प्रॉपर्टीज़ से नामांकित float मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | float[] | कस्टम प्रॉपर्टी मान |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

कस्टम प्रॉपर्टीज़ से नामांकित double मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिए कस्टम प्रॉपर्टी का नाम। |
| value | double[] | कस्टम प्रॉपर्टी मान |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

नामांकित boolean कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | boolean | कस्टम प्रॉपर्टी मान |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

नामांकित integer कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | int | कस्टम प्रॉपर्टी मान |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

नामांकित DateTime कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.util.Date | कस्टम प्रॉपर्टी मान |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

नामांकित स्ट्रिंग कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | java.lang.String | कस्टम प्रॉपर्टी मान |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

नामांकित float कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | float | कस्टम प्रॉपर्टी मान |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

नामांकित double कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिए कस्टम प्रॉपर्टी का नाम |
| value | double | कस्टम प्रॉपर्टी मान |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

सभी कस्टम प्रॉपर्टीज़ को हटाता है।

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

कस्टम दस्तावेज़ प्रॉपर्टीज़ (Microsoft Information Protection SDK Metadata) से सेंसेटिविटी लेबल्स की एरे प्राप्त करता है।

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // कस्टम डॉक्यूमेंट प्रॉपर्टीज़ से संवेदनशील लेबल प्राप्त करें
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // लेबल को संग्रह में जोड़ें
>          // यहाँ आप लेबल की जानकारी की वैधता (लेबल उपलब्ध है, आदि) की जाँच जोड़ सकते हैं
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

सभी बिल्ट-इन प्रॉपर्टीज़ को साफ़ करता है और डिफ़ॉल्ट मान सेट करता है।

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। थंबनेल को डिस्प्ले के अनुसार स्केल करने के लिए इस तत्व को **true** पर सेट करें। थंबनेल को केवल उन सेक्शन को दिखाने के लिए क्रॉप करने के लिए इस तत्व को **false** पर सेट करें। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। थंबनेल को डिस्प्ले के अनुसार स्केल करने के लिए इस तत्व को **true** पर सेट करें। थंबनेल को केवल उन सेक्शन को दिखाने के लिए क्रॉप करने के लिए इस तत्व को **false** पर सेट करें। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

दस्तावेज़ में हाइपरलिंक्स के अद्यतन स्थिति को दर्शाता है। हाइपरलिंक्स को अपडेटेड बताने के लिए इस तत्व को **true** पर सेट करें। हाइपरलिंक्स को पुराना बताने के लिए इस तत्व को **false** पर सेट करें। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
दस्तावेज़ में हाइपरलिंक अद्यतन हैं या नहीं दर्शाता है। इस तत्व को **true** सेट करें यह संकेत देने के लिए कि हाइपरलिंक अपडेट किए गए हैं। इस तत्व को **false** सेट करें यह संकेत देने के लिए कि हाइपरलिंक पुरानी हैं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग द्वारा एक निर्माता द्वारा अपडेट किए गए थे। इस दस्तावेज़ को खोलने वाला अगला निर्माता इस भाग में निर्दिष्ट नए हाइपरलिंक के साथ हाइपरलिंक संबंधों को अपडेट करेगा। पढ़ें/लिखें बूलियन।

**रिटर्न:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग द्वारा एक निर्माता द्वारा अपडेट किए गए थे। इस दस्तावेज़ को खोलने वाला अगला निर्माता इस भाग में निर्दिष्ट नए हाइपरलिंक के साथ हाइपरलिंक संबंधों को अपडेट करेगा। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

एक प्रस्तुति दस्तावेज़ में कुल स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

एक प्रस्तुति दस्तावेज़ में छिपी स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getNotes() {#getNotes--}
```
public final int getNotes()
```

एक प्रस्तुति में नोट्स वाले स्लाइडों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

यदि लागू हो तो दस्तावेज़ में पाए गए कुल पैराग्राफों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getWords() {#getWords--}
```
public final int getWords()
```

एक दस्तावेज़ में सम्मिलित कुल शब्दों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

दस्तावेज़ में उपस्थित ध्वनि या वीडियो क्लिपों की कुल संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग दस्तावेज़ भाग नहीं हैं बल्कि दस्तावेज़ अनुभागों की अवधारणात्मक प्रतिनिधित्व हैं। केवल-पढ़ने योग्य String[]।

**रिटर्न:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

दस्तावेज़ भागों का समूहबद्ध करने और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल-पढ़ने योग्य IHeadingPair[]।

**रिटर्न:**
com.aspose.slides.IHeadingPair[]

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

वर्तमान ऑब्जेक्ट को क्लोन करता है

**रिटर्न:**
java.lang.Object - क्लोन

### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

वर्तमान ऑब्जेक्ट को क्लोन करता है

**रिटर्न:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - क्लोन