---
title: Connector
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के द्वारा
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/connector/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)  
```
public class Connector extends GeometryShape implements IConnector
```

एक कनेक्टर का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | आकृति के लॉक को लौटाता है। |
| [getConnectorLock()](#getConnectorLock--) | कनेक्टर के लॉक को लौटाता है। |
| [getShapeType()](#getShapeType--) | AutoShape प्रकार को लौटाता है या सेट करता है। |
| [setShapeType(int value)](#setShapeType-int-) | AutoShape प्रकार को लौटाता है या सेट करता है। |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | कनेक्टर की शुरुआत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | कनेक्टर की शुरुआत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | कनेक्टर के अंत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | कनेक्टर के अंत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | प्रारंभिक आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | प्रारंभिक आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | अंतिम आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | अंतिम आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [reroute()](#reroute--) | कनेक्टर को पुनर्निर्देशित करता है ताकि वह जुड़े हुए आकृतियों के बीच सबसे छोटा संभव मार्ग ले। |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

आकृति के लॉक को लौटाता है। केवल-पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**रिटर्न:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

कनेक्टर के लॉक को लौटाता है। केवल-पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**रिटर्न:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

AutoShape प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ShapeType](../../com.aspose.slides/shapetype).

**रिटर्न:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

AutoShape प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ShapeType](../../com.aspose.slides/shapetype).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

कनेक्टर की शुरुआत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape).

**रिटर्न:**  
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

कनेक्टर की शुरुआत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

कनेक्टर के अंत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape).

**रिटर्न:**  
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

कनेक्टर के अंत से संलग्न करने हेतु आकृति को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

प्रारंभिक आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long.

**रिटर्न:**  
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

प्रारंभिक आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

अंतिम आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long.

**रिटर्न:**  
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

अंतिम आकृति के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

कनेक्टर को पुनर्निर्देशित करता है ताकि वह जुड़े हुए आकृतियों के बीच सबसे छोटा संभव मार्ग ले।