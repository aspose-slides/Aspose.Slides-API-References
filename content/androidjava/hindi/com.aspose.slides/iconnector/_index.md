---
title: IConnector
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iconnector/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

एक कनेक्टर का प्रतिनिधित्व करता है।

## विधियों

| विधि | विवरण |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | shape के लॉक लौटाता है। |
| [getConnectorLock()](#getConnectorLock--) | Connector के लॉक लौटाता है। |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | shape को कनेक्टर की शुरुआत से जोड़ने के लिए लौटाता है या सेट करता है। |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | shape को कनेक्टर की शुरुआत से जोड़ने के लिए लौटाता है या सेट करता है। |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | shape को कनेक्टर के अंत से जोड़ने के लिए लौटाता है या सेट करता है। |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | shape को कनेक्टर के अंत से जोड़ने के लिए लौटाता है या सेट करता है। |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | प्रारम्भिक shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | प्रारम्भिक shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | अंतिम shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | अंतिम shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। |
| [reroute()](#reroute--) | कनेक्टर को इस प्रकार पुनः मार्गित करता है कि वह जुड़ी हुई आकृतियों के बीच सबसे छोटा संभावित मार्ग ले। |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


shape के लॉक लौटाता है। केवल पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock)।

**वापसी:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Connector के लॉक लौटाता है। केवल पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock)।

**वापसी:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


shape को कनेक्टर की शुरुआत से जोड़ने के लिए लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


shape को कनेक्टर की शुरुआत से जोड़ने के लिए लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


shape को कनेक्टर के अंत से जोड़ने के लिए लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


shape को कनेक्टर के अंत से जोड़ने के लिए लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


प्रारम्भिक shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**वापसी:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


प्रारम्भिक shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


अंतिम shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**वापसी:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


अंतिम shape के कनेक्शन साइट का इंडेक्स लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


कनेक्टर को इस प्रकार पुनः मार्गित करता है कि वह जुड़ी हुई आकृतियों के बीच सबसे छोटा संभावित मार्ग ले।