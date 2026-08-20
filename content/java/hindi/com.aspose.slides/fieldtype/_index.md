---
title: FieldType
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: फ़ील्ड का एक प्रकार दर्शाता है।
type: docs
url: /hi/com.aspose.slides/fieldtype/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)  
```
public final class FieldType implements IFieldType
```

फ़ील्ड का एक प्रकार दर्शाता है। यह मान निर्धारित करता है कि जब फ़ील्ड को अद्यतन किया जाएगा तो फ़ील्ड भाग में कौन सा पाठ सेट किया जाएगा।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | FieldType वर्ग का नया उदाहरण आरंभ करता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInternalString()](#getInternalString--) | इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | जांचता है कि यह फ़ील्ड किसी अन्य के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | इस ऑब्जेक्ट के लिए हैशकोड लौटाता है। |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | जांचता है कि दो FieldType ऑब्जेक्ट बराबर हैं या नहीं। |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | जांचता है कि दो FieldType ऑब्जेक्ट असमान हैं या नहीं। |
| [getSlideNumber()](#getSlideNumber--) | वर्तमान स्लाइड संख्या। |
| [getFooter()](#getFooter--) | स्लाइड का फ़ूटर। |
| [getHeader()](#getHeader--) | स्लाइड का हेडर। |
| [getDateTime()](#getDateTime--) | रेंडरिंग एप्लिकेशन के लिए डिफ़ॉल्ट दिनांक-समय प्रारूप में वर्तमान तिथि और समय। |
| [getDateTime1()](#getDateTime1--) | पहले पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये MM/DD/YYYY) में वर्तमान तिथि और समय। |
| [getDateTime2()](#getDateTime2--) | दूसरे पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये Day, Month DD, YYYY) में वर्तमान तिथि और समय। |
| [getDateTime3()](#getDateTime3--) | तीसरे पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये DD Month YYYY) में वर्तमान तिथि और समय। |
| [getDateTime4()](#getDateTime4--) | चौथे पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये Month DD, YYYY) में वर्तमान तिथि और समय। |
| [getDateTime5()](#getDateTime5--) | पाँचवें पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये DD-Mon-YY) में वर्तमान तिथि और समय। |
| [getDateTime6()](#getDateTime6--) | छठे पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये Month YY) में वर्तमान तिथि और समय। |
| [getDateTime7()](#getDateTime7--) | सातवें पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये Mon-YY) में वर्तमान तिथि और समय। |
| [getDateTime8()](#getDateTime8--) | आठवें पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये MM/DD/YYYY hh:mm AM/PM) में वर्तमान तिथि और समय। |
| [getDateTime9()](#getDateTime9--) | नववें पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये MM/DD/YYYY hh:mm:ss AM/PM) में वर्तमान तिथि और समय। |
| [getDateTime10()](#getDateTime10--) | दसवें पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये hh:mm) में वर्तमान तिथि और समय। |
| [getDateTime11()](#getDateTime11--) | ग्यारहवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm:ss) में वर्तमान तिथि और समय। |
| [getDateTime12()](#getDateTime12--) | बारहवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm AM/PM) में वर्तमान तिथि और समय। |
| [getDateTime13()](#getDateTime13--) | तेरहवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm:ss AM/PM) में वर्तमान तिथि और समय। |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

FieldType वर्ग का नया उदाहरण आरंभ करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। पढ़ें/लिखें स्ट्रिंग।

**रिटर्न:**  
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। पढ़ें/लिखें स्ट्रिंग।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

जांचता है कि यह फ़ील्ड किसी अन्य के बराबर है या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने वाला फ़ील्ड। |

**रिटर्न:**  
boolean - यदि फ़ील्ड समान हों तो True।

### hashCode() {#hashCode--}
```
public int hashCode()
```

इस ऑब्जेक्ट के लिए हैशकोड लौटाता है।

**रिटर्न:**  
int - हैशकोड int।

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

जांचता है कि दो FieldType ऑब्जेक्ट बराबर हैं या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने वाला पहला FieldType। |
| b | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने वाला दूसरा FieldType। |

**रिटर्न:**  
boolean - यदि FieldType ऑब्जेक्ट समान हों तो True।

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

जांचता है कि दो FieldType ऑब्जेक्ट असमान हैं या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने वाला पहला FieldType। |
| b | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने वाला दूसरा FieldType। |

**रिटर्न:**  
boolean - यदि FieldType ऑब्जेक्ट समान नहीं हों तो True।

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

वर्तमान स्लाइड संख्या। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

स्लाइड का फ़ूटर। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldName getHeader()
```

स्लाइड का हेडर। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

रेंडरिंग एप्लिकेशन के लिए डिफ़ॉल्ट दिनांक-समय प्रारूप में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

पहले पूर्वनिर्धारित प्रारूप (अंग्रेज़ी के लिये MM/DD/YYYY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

दूसरे पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये Day, Month DD, YYYY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

तीसरे पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये DD Month YYYY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

चौथे पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये Month DD, YYYY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

पाँचवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये DD-Mon-YY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

छठे पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये Month YY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

सातवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये Mon-YY) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

आठवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये MM/DD/YYYY hh:mm AM/PM) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

नववें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये MM/DD/YYYY hh:mm:ss AM/PM) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

दसवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

ग्यारहवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm:ss) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

बारहवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm AM/PM) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

तेरहवें पूर्वनिर्धारित स्वरूप (अंग्रेज़ी के लिये hh:mm:ss AM/PM) में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](../../com.aspose.slides/fieldtype)।

**रिटर्न:**  
[FieldType](../../com.aspose.slides/fieldtype)