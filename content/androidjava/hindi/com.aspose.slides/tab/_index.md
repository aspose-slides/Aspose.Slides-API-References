---
title: Tab
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: किसी पाठ के लिए टैबुलेशन का प्रतिनिधित्व करता है।
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

Represents a tabulation for a text.
## निर्माता

| Constructor | Description |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Creates new Tab |
## विधियाँ

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returns or sets position of a tab. |
| [setPosition(double value)](#setPosition-double-) | Returns or sets position of a tab. |
| [getAlignment()](#getAlignment--) | Returns or sets align style of a tab. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets align style of a tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the current instance with another object of the same type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

नया Tab बनाता है

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Align. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long.

**वापसी:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Returns or sets position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read/write double.

**वापसी:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Returns or sets position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Returns or sets align style of a tab. Read/write [TabAlignment](../../com.aspose.slides/tabalignment).

**वापसी:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Returns or sets align style of a tab. Read/write [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Compares the current instance with another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An object to compare with this instance. |

**वापसी:**
int - A 32-bit integer that indicates the relative order of the comparands. The return value has these meanings: 

 *  < 0 - This instance is less than obj.
 *  = 0 - This instance is equal to obj.
 *  > 0 - This instance is greater than obj.