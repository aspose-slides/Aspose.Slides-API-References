---
title: Tab
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक पाठ के लिए टैब का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/tab/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

एक पाठ के लिए टैब का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| Constructor | Description |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | नया Tab बनाता है। |
## विधियाँ

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | एक टैब की स्थिति लौटाता है या सेट करता है। |
| [setPosition(double value)](#setPosition-double-) | एक टैब की स्थिति लौटाता है या सेट करता है। |
| [getAlignment()](#getAlignment--) | एक टैब की संरेखण शैली को लौटाता है या सेट करता है। |
| [setAlignment(int value)](#setAlignment-int-) | एक टैब की संरेखण शैली को लौटाता है या सेट करता है। |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | वर्तमान इंस्टेंस की तुलना उसी प्रकार के अन्य ऑब्जेक्ट से करता है। |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


नया Tab बनाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double | टैब स्थिति। |
| align | int | संरेखण। |

### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। पढ़ने-के-लिए-केवल long।

**Returns:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


एक टैब की स्थिति लौटाता है या सेट करता है। इस प्रॉपर्टी को असाइन करने से संग्रह में टैब का इंडेक्स बदल सकता है और एन्यूमरेटर अमान्य हो सकता है। पढ़ें/लिखें double।

**Returns:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


एक टैब की स्थिति लौटाता है या सेट करता है। इस प्रॉपर्टी को असाइन करने से संग्रह में टैब का इंडेक्स बदल सकता है और एन्यूमरेटर अमान्य हो सकता है। पढ़ें/लिखें double।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


एक टैब की संरेखण शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [TabAlignment](../../com.aspose.slides/tabalignment)।

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


एक टैब की संरेखण शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [TabAlignment](../../com.aspose.slides/tabalignment)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


वर्तमान इंस्टेंस की तुलना उसी प्रकार के अन्य ऑब्जेक्ट से करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक ऑब्जेक्ट। |

**Returns:**
int - एक 32-बिट पूर्णांक जो तुलना किए गए तत्वों के सापेक्ष क्रम को दर्शाता है। रिटर्न मान के अर्थ इस प्रकार हैं:

 *  < 0 - यह इंस्टेंस obj से छोटा है।
 *  = 0 - यह इंस्टेंस obj के बराबर है।
 *  > 0 - यह इंस्टेंस obj से बड़ा है।