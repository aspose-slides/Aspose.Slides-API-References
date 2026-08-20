---
title: Connector
second_title: Aspose.Slides for Java API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/connector/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**  
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)  
```
public class Connector extends GeometryShape implements IConnector
```

एक कनेक्टर का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | आकार के लॉक लौटाता है। |
| [getConnectorLock()](#getConnectorLock--) | कनेक्टर के लॉक लौटाता है। |
| [getShapeType()](#getShapeType--) | AutoShape प्रकार को लौटाता है या सेट करता है। |
| [setShapeType(int value)](#setShapeType-int-) | AutoShape प्रकार को लौटाता है या सेट करता है। |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | प्रारंभिक आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | प्रारंभिक आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | अंतिम आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | अंतिम आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [reroute()](#reroute--) | कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए आकारों के बीच सबसे छोटा संभव मार्ग ले। |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

आकार के लॉक लौटाता है। केवल पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock)।

**वापसी:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

कनेक्टर के लॉक लौटाता है। केवल पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock)।

**वापसी:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

AutoShape प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ShapeType](../../com.aspose.slides/shapetype)।

**वापसी:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

AutoShape प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ShapeType](../../com.aspose.slides/shapetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**  
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**  
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

प्रारंभिक आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**वापसी:**  
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

प्रारंभिक आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

अंतिम आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**वापसी:**  
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

अंतिम आकार के लिये कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए आकारों के बीच सबसे छोटा संभव मार्ग ले।