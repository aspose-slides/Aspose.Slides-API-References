---
title: OleObjectFrame
second_title: Java API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: स्लाइड पर एक OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/oleobjectframe/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

स्लाइड पर एक OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // PPTX को एक प्रस्तुति ऑब्जेक्ट में लोड करता है
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // शेप को OleObjectFrame में कास्ट करता है
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // OLE ऑब्जेक्ट को पढ़ता है और डिस्क पर लिखता है
>      if (oleObjectFrame != null) {
>          // एम्बेडेड फाइल डेटा प्राप्त करता है
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // एम्बेडेड फाइल एक्स्टेंशन प्राप्त करता है
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // निकाले गए फाइल को सहेजने के लिए पाथ बनाता है
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // निकाला गया डेटा सहेजता है
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject आइकन के शीर्षक को प्राप्त या सेट करता है। |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject आइकन के शीर्षक को प्राप्त या सेट करता है। |
| [getObjectName()](#getObjectName--) | ऑब्जेक्ट के नाम को प्राप्त या सेट करता है। |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | ऑब्जेक्ट के नाम को प्राप्त या सेट करता है। |
| [getObjectProgId()](#getObjectProgId--) | ऑब्जेक्ट के ProgID को लौटाता है। |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ऑब्जेक्ट के ProgID को लौटाता है। |
| [getLinkFileName()](#getLinkFileName--) | लिंक्ड फ़ाइल का पूरा पाथ लौटाता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक्ड फ़ाइल का पूरा पाथ लौटाता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | लिंक्ड फ़ाइल का पूरा पाथ लौटाता है। |
| [getLinkPathRelative()](#getLinkPathRelative--) | यदि मौजूद हो तो लिंक्ड फ़ाइल का सापेक्ष पाथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | एम्बेडेड OLE ऑब्जेक्ट की फ़ाइल नाम लौटाता है। |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | एम्बेडेड OLE ऑब्जेक्ट का पाथ लौटाता है। |
| [getEmbeddedData()](#getEmbeddedData--) | OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त या सेट करता है। |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है। |
| [isObjectIcon()](#isObjectIcon--) | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखता है या नहीं। |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखता है या नहीं। |
| [isObjectLink()](#isObjectLink--) | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से लिंक्ड है या नहीं। |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | निर्धारित करता है कि जब प्रेजेंटेशन खोला या प्रिंट किया जाता है तो लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | निर्धारित करता है कि जब प्रेजेंटेशन खोला या प्रिंट किया जाता है तो लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**रिटर्न:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

OleObject आइकन के शीर्षक को प्राप्त या सेट करता है। पढ़ने-लिखने योग्य String.

--------------------

जब IsObjectIcon == false हो तो यह मान अनदेखा किया जाता है। स्ट्रिंग को Ole आइकन के आकार के अनुसार छोटा किया जा सकता है।

**रिटर्न:**  
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

OleObject आइकन के शीर्षक को प्राप्त या सेट करता है। पढ़ने-लिखने योग्य String.

--------------------

जब IsObjectIcon == false हो तो यह मान अनदेखा किया जाता है। स्ट्रिंग को Ole आइकन के आकार के अनुसार छोटा किया जा सकता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

ऑब्जेक्ट के नाम को प्राप्त या सेट करता है। पढ़ने-लिखने योग्य String.

**रिटर्न:**  
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

ऑब्जेक्ट के नाम को प्राप्त या सेट करता है। पढ़ने-लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

ऑब्जेक्ट के ProgID को लौटाता है। केवल-पढ़ने योग्य String.

**रिटर्न:**  
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

ऑब्जेक्ट के ProgID को लौटाता है। केवल-पढ़ने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

लिंक्ड फ़ाइल का पूरा पाथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल-पढ़ने योग्य String.

**रिटर्न:**  
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

लिंक्ड फ़ाइल का पूरा पाथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ने-लिखने योग्य String.

**रिटर्न:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

लिंक्ड फ़ाइल का पूरा पाथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ने-लिखने योग्य String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

यदि मौजूद हो तो लिंक्ड फ़ाइल का सापेक्ष पाथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल-पढ़ने योग्य String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

Ppt प्रेजेंटेशनों में, कुछ Ole ऑब्जेक्ट लिंक का सापेक्ष प्रतिनिधित्व हो सकता है।

**रिटर्न:**  
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

एम्बेडेड OLE ऑब्जेक्ट की फ़ाइल नाम लौटाता है।

**रिटर्न:**  
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

एम्बेडेड OLE ऑब्जेक्ट का पाथ लौटाता है।

**रिटर्न:**  
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त या सेट करता है। पढ़ने-लिखने योग्य [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**रिटर्न:**  
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है।

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नए डेटा के अनुसार बदलता है और IsObjectLink फ़्लैग को false सेट करता है, जिससे OLE ऑब्जेक्ट एम्बेडेड बन जाता है। |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखता है या नहीं। पढ़ने-लिखने योग्य boolean .

**रिटर्न:**  
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखता है या नहीं। पढ़ने-लिखने योग्य boolean .

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से लिंक्ड है या नहीं। केवल-पढ़ने योग्य boolean .

**रिटर्न:**  
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

निर्धारित करता है कि जब प्रेजेंटेशन खोला या प्रिंट किया जाता है तो लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। पढ़ने-लिखने योग्य boolean .

**रिटर्न:**  
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

निर्धारित करता है कि जब प्रेजेंटेशन खोला या प्रिंट किया जाता है तो लिंक्ड एम्बेडेड ऑब्जेक्ट स्वचालित रूप से अपडेट होता है या नहीं। पढ़ने-लिखने योग्य boolean .

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |