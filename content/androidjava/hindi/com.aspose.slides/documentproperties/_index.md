---
title: DocumentProperties
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रस्तुति की गुणों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/documentproperties/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

प्रस्तुति के गुणों को दर्शाता है।

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Presentation क्लास को इनस्टैंशिएट करें जो प्रस्तुति को दर्शाती है
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Presentation से जुड़े IDocumentProperties ऑब्जेक्ट का रेफ़रेंस बनाएं
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // बिल्ट-इन प्रॉपर्टी प्रदर्शित करें
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
>  // Presentation क्लास को इनस्टैंशिएट करें जो प्रस्तुति को दर्शाती है
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Presentation से जुड़े IDocumentProperties ऑब्जेक्ट का रेफ़रेंस बनाएं
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // बिल्ट-इन प्रॉपर्टी सेट करें
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // अपनी प्रस्तुति को फ़ाइल में सहेजें
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | क्लास [DocumentProperties](../../com.aspose.slides/documentproperties) का नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | ऐप संस्करण को लौटाता है। |
| [getNameOfApplication()](#getNameOfApplication--) | एप्लिकेशन का नाम लौटाता या सेट करता है। |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | एप्लिकेशन का नाम लौटाता या सेट करता है। |
| [getCompany()](#getCompany--) | कंपनी प्रॉपर्टी को लौटाता या सेट करता है। |
| [setCompany(String value)](#setCompany-java.lang.String-) | कंपनी प्रॉपर्टी को लौटाता या सेट करता है। |
| [getManager()](#getManager--) | मैनेजर प्रॉपर्टी को लौटाता या सेट करता है। |
| [setManager(String value)](#setManager-java.lang.String-) | मैनेजर प्रॉपर्टी को लौटाता या सेट करता है। |
| [getPresentationFormat()](#getPresentationFormat--) | प्रस्तुति के इच्छित फॉर्मेट को लौटाता या सेट करता है। |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | प्रस्तुति के इच्छित फॉर्मेट को लौटाता या सेट करता है। |
| [getSharedDoc()](#getSharedDoc--) | निर्धारत करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | निर्धारत करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। |
| [getApplicationTemplate()](#getApplicationTemplate--) | एप्लिकेशन का टेम्प्लेट लौटाता या सेट करता है। |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | एप्लिकेशन का टेम्प्लेट लौटाता या सेट करता है। |
| [getTotalEditingTime()](#getTotalEditingTime--) | प्रस्तुति का कुल संपादन समय। |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | प्रस्तुति का कुल संपादन समय। |
| [getTitle()](#getTitle--) | प्रस्तुति का शीर्षक लौटाता या सेट करता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | प्रस्तुति का शीर्षक लौटाता या सेट करता है। |
| [getSubject()](#getSubject--) | प्रस्तुति का विषय लौटाता या सेट करता है। |
| [setSubject(String value)](#setSubject-java.lang.String-) | प्रस्तुति का विषय लौटाता या सेट करता है। |
| [getAuthor()](#getAuthor--) | प्रस्तुति के लेखक को लौटाता या सेट करता है। |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | प्रस्तुति के लेखक को लौटाता या सेट करता है। |
| [getKeywords()](#getKeywords--) | प्रस्तुति के कीवर्ड्स को लौटाता या सेट करता है। |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | प्रस्तुति के कीवर्ड्स को लौटाता या सेट करता है। |
| [getComments()](#getComments--) | प्रस्तुति की टिप्पणियों को लौटाता या सेट करता है। |
| [setComments(String value)](#setComments-java.lang.String-) | प्रस्तुति की टिप्पणियों को लौटाता या सेट करता है। |
| [getCategory()](#getCategory--) | प्रस्तुति की श्रेणी को लौटाता या सेट करता है। |
| [setCategory(String value)](#setCategory-java.lang.String-) | प्रस्तुति की श्रेणी को लौटाता या सेट करता है। |
| [getCreatedTime()](#getCreatedTime--) | प्रस्तुति के निर्मित होने की तिथि लौटाता है। |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | प्रस्तुति के निर्मित होने की तिथि लौटाता है। |
| [getLastSavedTime()](#getLastSavedTime--) | प्रस्तुति के अंतिम संशोधित होने की तिथि लौटाता है। |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | प्रस्तुति के अंतिम संशोधित होने की तिथि लौटाता है। |
| [getLastPrinted()](#getLastPrinted--) | प्रस्तुति के अंतिम प्रिंट किए जाने की तिथि लौटाता है। |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | प्रस्तुति के अंतिम प्रिंट किए जाने की तिथि लौटाता है। |
| [getLastSavedBy()](#getLastSavedBy--) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता या सेट करता है। |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता या सेट करता है। |
| [getRevisionNumber()](#getRevisionNumber--) | प्रस्तुति के संशोधन संख्या को लौटाता या सेट करता है। |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | प्रस्तुति के संशोधन संख्या को लौटाता या सेट करता है। |
| [getContentStatus()](#getContentStatus--) | प्रस्तुति की कंटेंट स्थिति को लौटाता या सेट करता है। |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | प्रस्तुति की कंटेंट स्थिति को लौटाता या सेट करता है। |
| [getContentType()](#getContentType--) | प्रस्तुति के कंटेंट प्रकार को लौटाता या सेट करता है। |
| [setContentType(String value)](#setContentType-java.lang.String-) | प्रस्तुति के कंटेंट प्रकार को लौटाता या सेट करता है। |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase दस्तावेज़ प्रॉपर्टी को लौटाता या सेट करता है। |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase दस्तावेज़ प्रॉपर्टी को लौटाता या सेट करता है। |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | कलेक्शन में वास्तविक रूप से मौजूद कस्टम प्रॉपर्टी की संख्या लौटाता है। |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | निर्दिष्ट इंडेक्स पर एक कस्टम प्रॉपर्टी नाम लौटाता है। |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | निर्दिष्ट नाम से संबद्ध कस्टम प्रॉपर्टी को हटाता है। |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी की उपस्थिति जाँचता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को लौटाता या सेट करता है। |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को लौटाता या सेट करता है। |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | नामित बूलियन कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | नामित पूर्णांक कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | नामित DateTime कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | नामित स्ट्रिंग कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | नामित फ़्लोट कस्टम प्रॉपर्टी सेट करता है। |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | नामित डबल कस्टम प्रॉपर्टी सेट करता है। |
| [clearCustomProperties()](#clearCustomProperties--) | सभी कस्टम प्रॉपर्टी हटाता है। |
| [getSensitivityLabels()](#getSensitivityLabels--) | कस्टम दस्तावेज़ प्रॉपर्टी से संवेदनशीलता लेबल की एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)। |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | सभी builtIn प्रॉपर्टी को साफ करता है और डिफ़ॉल्ट मान सेट करता है। |
| [getScaleCrop()](#getScaleCrop--) | दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। |
| [getLinksUpToDate()](#getLinksUpToDate--) | दस्तावेज़ में हाइपरलिंक्स की अद्यतन स्थिति दर्शाता है। |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | दस्तावेज़ में हाइपरलिंक्स की अद्यतन स्थिति दर्शाता है। |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में प्रोड्यूसर द्वारा अपडेट किए गए थे। |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में प्रोड्यूसर द्वारा अपडेट किए गए थे। |
| [getSlides()](#getSlides--) | प्रस्तुति दस्तावेज़ में स्लाइड्स की कुल संख्या लौटाता है। |
| [getHiddenSlides()](#getHiddenSlides--) | प्रस्तुति दस्तावेज़ में छिपी हुई स्लाइड्स की संख्या लौटाता है। |
| [getNotes()](#getNotes--) | नोट्स वाले स्लाइड्स की संख्या लौटाता है। |
| [getParagraphs()](#getParagraphs--) | यदि लागू हो तो दस्तावेज़ में पाए गए पैराग्राफ की कुल संख्या लौटाता है। |
| [getWords()](#getWords--) | दस्तावेज़ में शब्दों की कुल संख्या लौटाता है। |
| [getMultimediaClips()](#getMultimediaClips--) | दस्तावेज़ में मौजूद ध्वनि या वीडियो क्लिप की कुल संख्या लौटाता है। |
| [getTitlesOfParts()](#getTitlesOfParts--) | प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। |
| [getHeadingPairs()](#getHeadingPairs--) | दस्तावेज़ भागों के समूहण और प्रत्येक समूह में भागों की संख्या दर्शाता है। |
| [deepClone()](#deepClone--) | वर्तमान ऑब्जेक्ट को क्लोन करता है |
| [cloneT()](#cloneT--) | वर्तमान ऑब्जेक्ट को क्लोन करता है |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

क्लास [DocumentProperties](../../com.aspose.slides/documentproperties) का नया उदाहरण आरंभ करता है।

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

ऐप संस्करण को लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

एप्लिकेशन का नाम लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

एप्लिकेशन का नाम लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

कंपनी प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

कंपनी प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

मैनेजर प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

मैनेजर प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

प्रस्तुति के इच्छित फॉर्मेट को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

प्रस्तुति के इच्छित फॉर्मेट को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ने-और-लिखने योग्य boolean.

**रिटर्न:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

निर्धारित करता है कि प्रस्तुति कई लोगों के बीच साझा है या नहीं। पढ़ने-और-लिखने योग्य boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

एप्लिकेशन का टेम्प्लेट लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

एप्लिकेशन का टेम्प्लेट लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

प्रस्तुति का कुल संपादन समय। पढ़ने-और-लिखने योग्य double.

**रिटर्न:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

प्रस्तुति का कुल संपादन समय। पढ़ने-और-लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

प्रस्तुति का शीर्षक लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

प्रस्तुति का शीर्षक लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

प्रस्तुति का विषय लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

प्रस्तुति का विषय लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

प्रस्तुति के लेखक को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

प्रस्तुति के लेखक को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

प्रस्तुति के कीवर्ड्स को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

प्रस्तुति के कीवर्ड्स को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

प्रस्तुति की टिप्पणियों को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

प्रस्तुति की टिप्पणियों को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

प्रस्तुति की श्रेणी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

प्रस्तुति की श्रेणी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

प्रस्तुति के निर्मित होने की तिथि लौटाता है। मान UTC में होते हैं। पढ़ने-और-लिखने योग्य java.util.Date.

**रिटर्न:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

प्रस्तुति के निर्मित होने की तिथि सेट करता है। मान UTC में होते हैं। पढ़ने-और-लिखने योग्य java.util.Date.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

प्रस्तुति के अंतिम संशोधित होने की तिथि लौटाता है। मान UTC में होते हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट होता है)। इसे मेथड [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाए गए DocumentProperties इंस्टेंस के माध्यम से बदला जा सकता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) मेथड सारांश में उदाहरण देखें।

**रिटर्न:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

प्रस्तुति के अंतिम संशोधित होने की तिथि सेट करता है। मान UTC में होते हैं। Presentation.DocumentProperties के मामले में केवल-पढ़ने योग्य (क्योंकि यह IPresentation ऑब्जेक्ट सहेजने की प्रक्रिया के दौरान आंतरिक रूप से अपडेट होता है)। इसे मेथड [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) द्वारा लौटाए गए DocumentProperties इंस्टेंस के माध्यम से बदला जा सकता है। कृपया [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) मेथड सारांश में उदाहरण देखें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

प्रस्तुति के अंतिम प्रिंट किए जाने की तिथि लौटाता है। पढ़ने-और-लिखने योग्य java.util.Date.

**रिटर्न:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

प्रस्तुति के अंतिम प्रिंट किए जाने की तिथि सेट करता है। पढ़ने-और-लिखने योग्य java.util.Date.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

प्रस्तुति को अंतिम बार संशोधित करने वाले व्यक्ति का नाम लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

प्रस्तुति के संशोधन संख्या को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य int.

**रिटर्न:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

प्रस्तुति के संशोधन संख्या को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

प्रस्तुति की कंटेंट स्थिति को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

प्रस्तुति की कंटेंट स्थिति को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

प्रस्तुति के कंटेंट प्रकार को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

प्रस्तुति के कंटेंट प्रकार को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

HyperlinkBase दस्तावेज़ प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**रिटर्न:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

HyperlinkBase दस्तावेज़ प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

कलेक्शन में वास्तविक रूप से मौजूद कस्टम प्रॉपर्टी की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

निर्दिष्ट इंडेक्स पर एक कस्टम प्रॉपर्टी नाम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | प्राप्त करने के लिये कस्टम प्रॉपर्टी का शून्य-आधारित इंडेक्स। |

**रिटर्न:**
java.lang.String - निर्दिष्ट इंडेक्स पर कस्टम प्रॉपर्टी नाम।
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

निर्दिष्ट नाम से संबद्ध कस्टम प्रॉपर्टी को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिये कस्टम प्रॉपर्टी का नाम। |

**रिटर्न:**
boolean - यदि प्रॉपर्टी हटाई गई तो true, अन्यथा false।
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

निर्दिष्ट नाम वाले कस्टम प्रॉपर्टी की उपस्थिति जाँचता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | जांचने के लिये कस्टम प्रॉपर्टी का नाम। |

**रिटर्न:**
boolean - यदि प्रॉपर्टी मौजूद है तो true, अन्यथा false।
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**रिटर्न:**
java.lang.Object

Value can be **int**, **float**, **String**, **boolean** or **Date**.

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

निर्दिष्ट नाम से जुड़ी कस्टम प्रॉपर्टी को लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

नामित बूलियन कस्टम प्रॉपर्टी का मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | boolean[] | कस्टम प्रॉपर्टी मान |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

नामित पूर्णांक कस्टम प्रॉपर्टी का मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | int[] | कस्टम प्रॉपर्टी मान |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

नामित DateTime कस्टम प्रॉपर्टी का मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | java.util.Date[] | कस्टम प्रॉपर्टी मान |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

नामित स्ट्रिंग कस्टम प्रॉपर्टी का मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | java.lang.String[] | कस्टम प्रॉपर्टी मान |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

नामित फ़्लोट कस्टम प्रॉपर्टी का मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | float[] | कस्टम प्रॉपर्टी मान |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

नामित डबल कस्टम प्रॉपर्टी का मान प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्राप्त करने के लिये कस्टम प्रॉपर्टी का नाम। |
| value | double[] | कस्टम प्रॉपर्टी मान |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

नामित बूलियन कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | boolean | कस्टम प्रॉपर्टी मान |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

नामित पूर्णांक कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | int | कस्टम प्रॉपर्टी मान |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

नामित DateTime कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | java.util.Date | कस्टम प्रॉपर्टी मान |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

नामित स्ट्रिंग कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | java.lang.String | कस्टम प्रॉपर्टी मान |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

नामित फ़्लोट कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | float | कस्टम प्रॉपर्टी मान |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

नामित डबल कस्टम प्रॉपर्टी सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | सेट करने के लिये कस्टम प्रॉपर्टी का नाम |
| value | double | कस्टम प्रॉपर्टी मान |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

सभी कस्टम प्रॉपर्टी हटाता है।
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

कस्टम दस्तावेज़ प्रॉपर्टी से संवेदनशीलता लेबल की एरे प्राप्त करता है (Microsoft Information Protection SDK Metadata)।

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // कस्टम दस्तावेज़ प्रॉपर्टीज़ से संवेदनशीलता लेबल प्राप्त करें
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // लेबल को संग्रह में जोड़ें
>          // यहाँ आप लेबल जानकारी की वैधता (लेबल उपलब्ध है आदि) की जाँच जोड़ सकते हैं
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

सभी builtIn प्रॉपर्टी को साफ करता है और डिफ़ॉल्ट मान सेट करता है।
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। इस मान को **true** सेट करने पर थंबनेल स्केल हो जाता है। इस मान को **false** सेट करने पर थंबनेल क्रॉप हो जाता है ताकि केवल वह भाग दिखे जो डिस्प्ले में फिट हो। पढ़ने-और-लिखने योग्य boolean.

**रिटर्न:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

दस्तावेज़ थंबनेल के डिस्प्ले मोड को दर्शाता है। इस मान को **true** सेट करने पर थंबनेल स्केल हो जाता है। इस मान को **false** सेट करने पर थंबनेल क्रॉप हो जाता है ताकि केवल वह भाग दिखे जो डिस्प्ले में फिट हो। पढ़ने-और-लिखने योग्य boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

दस्तावेज़ में हाइपरलिंक्स की अद्यतन स्थिति दर्शाता है। इस मान को **true** सेट करने पर हाइपरलिंक्स अपडेटेड माने जाते हैं। इस मान को **false** सेट करने पर हाइपरलिंक्स पुराने माने जाते हैं। पढ़ने-और-लिखने योग्य boolean.

**रिटर्न:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

दस्तावेज़ में हाइपरलिंक्स की अद्यतन स्थिति दर्शाता है। इस मान को **true** सेट करने पर हाइपरलिंक्स अपडेटेड माने जाते हैं। इस मान को **false** सेट करने पर हाइपरलिंक्स पुराने माने जाते हैं। पढ़ने-और-लिखने योग्य boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में प्रोड्यूसर द्वारा अपडेट किए गए थे।

**रिटर्न:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

निर्दिष्ट करता है कि इस भाग में एक या अधिक हाइपरलिंक केवल इस भाग में प्रोड्यूसर द्वारा अपडेट किए गए थे।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

प्रस्तुति दस्तावेज़ में स्लाइड्स की कुल संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

छिपी हुई स्लाइड्स की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

नोट्स वाले स्लाइड्स की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

यदि लागू हो तो दस्तावेज़ में पाए गए पैराग्राफ की कुल संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

दस्तावेज़ में शब्दों की कुल संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

दस्तावेज़ में मौजूद ध्वनि या वीडियो क्लिप की कुल संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

प्रत्येक दस्तावेज़ भाग का शीर्षक निर्दिष्ट करता है। ये भाग वास्तविक दस्तावेज़ भाग नहीं हैं, बल्कि दस्तावेज़ अनुभागों के अवधारणात्मक प्रतिनिधित्व हैं। केवल-पढ़ने योग्य String[].

**रिटर्न:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

दस्तावेज़ भागों के समूहण और प्रत्येक समूह में भागों की संख्या दर्शाता है। केवल-पढ़ने योग्य IHeadingPair[].

**रिटर्न:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

वर्तमान ऑब्जेक्ट को क्लोन करता है

**रिटर्न:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

वर्तमान ऑब्जेक्ट को क्लोन करता है

**रिटर्न:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone