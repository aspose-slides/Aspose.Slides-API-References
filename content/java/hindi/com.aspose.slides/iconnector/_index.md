---
title: IConnector
second_title: Aspose.Slides for Java API संदर्भ
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
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | आकार के लॉक लौटाता है। |
| [getConnectorLock()](#getConnectorLock--) | कनेक्टर के लॉक लौटाता है। |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | प्रारंभिक आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | प्रारंभिक आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | अंतिम आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | अंतिम आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। |
| [reroute()](#reroute--) | कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए आकारों के बीच सबसे छोटा संभव मार्ग ले। |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock)।

**रिटर्न:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

कनेक्टर के लॉक लौटाता है। केवल-पढ़ने योग्य [IConnectorLock](../../com.aspose.slides/iconnectorlock)।

**रिटर्न:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

कनेक्टर की शुरुआत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

कनेक्टर के अंत को संलग्न करने वाले आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

प्रारंभिक आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**रिटर्न:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

प्रारंभिक आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

अंतिम आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**रिटर्न:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

अंतिम आकार के कनेक्शन साइट का सूचकांक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य long।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए आकारों के बीच सबसे छोटा संभव मार्ग ले।