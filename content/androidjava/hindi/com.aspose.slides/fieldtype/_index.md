---
title: FieldType
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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

फ़ील्ड का एक प्रकार दर्शाता है। यह मान निर्धारित करता है कि अपडेट होने पर फ़ील्ड भाग में कौन सा पाठ सेट किया जाएगा।

## निर्माता

| Constructor | Description |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | FieldType क्लास का नया उदाहरण आरंभ करता है। |

## विधियाँ

| Method | Description |
| --- | --- |
| [getInternalString()](#getInternalString--) | इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | जांचता है कि यह फ़ील्ड किसी अन्य के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | इस ऑब्जेक्ट के लिए हैशकोड लौटाता है। |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | जांचता है कि दो FieldType ऑब्जेक्ट बराबर हैं या नहीं। |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | जांचता है कि दो FieldType ऑब्जेक्ट असमान हैं या नहीं। |
| [getSlideNumber()](#getSlideNumber--) | वर्तमान स्लाइड का क्रमांक। |
| [getFooter()](#getFooter--) | स्लाइड का फ़ुटर। |
| [getHeader()](#getHeader--) | स्लाइड का हेडर। |
| [getDateTime()](#getDateTime--) | रेंडरिंग एप्लिकेशन के लिए डिफ़ॉल्ट दिनांक-समय प्रारूप में वर्तमान दिनांक और समय। |
| [getDateTime1()](#getDateTime1--) | प्रथम निर्धारित प्रारूप (MM/DD/YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime2()](#getDateTime2--) | द्वितीय निर्धारित प्रारूप (Day, Month DD, YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime3()](#getDateTime3--) | तृतीय निर्धारित प्रारूप (DD Month YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime4()](#getDateTime4--) | चतुर्थ निर्धारित प्रारूप (Month DD, YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime5()](#getDateTime5--) | पंचम निर्धारित प्रारूप (DD-Mon-YY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime6()](#getDateTime6--) | षष्ठ निर्धारित प्रारूप (Month YY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime7()](#getDateTime7--) | सप्तम निर्धारित प्रारूप (Mon-YY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime8()](#getDateTime8--) | अष्टम निर्धारित प्रारूप (MM/DD/YYYY hh:mm AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime9()](#getDateTime9--) | नवम निर्धारित प्रारूप (MM/DD/YYYY hh:mm:ss AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime10()](#getDateTime10--) | दशम निर्धारित प्रारूप (hh:mm अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime11()](#getDateTime11--) | एकादश निर्धारित प्रारूप (hh:mm:ss अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime12()](#getDateTime12--) | द्वादश निर्धारित प्रारूप (hh:mm AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |
| [getDateTime13()](#getDateTime13--) | तेरहवाँ निर्धारित प्रारूप (hh:mm:ss AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

FieldType क्लास का नया उदाहरण आरंभ करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

इस FieldType ऑब्जेक्ट का आंतरिक नाम लौटाता है। पढ़ें/लिखें String।

**वापसी:**  
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

इस FieldType ऑब्जेक्ट का आंतरिक नाम सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

जांचता है कि यह फ़ील्ड किसी अन्य के बराबर है या नहीं।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिये फ़ील्ड। |

**वापसी:**  
boolean - यदि फ़ील्ड समान हों तो true।

### hashCode() {#hashCode--}
```
public int hashCode()
```

इस ऑब्जेक्ट के लिए हैशकोड लौटाता है।

**वापसी:**  
int - हैशकोड।

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

जांचता है कि दो FieldType ऑब्जेक्ट बराबर हैं या नहीं।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने के लिये पहला FieldType। |
| b | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने के लिये दूसरा FieldType। |

**वापसी:**  
boolean - यदि FieldType ऑब्जेक्ट समान हों तो true।

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

जांचता है कि दो FieldType ऑब्जेक्ट असमान हैं या नहीं।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने के लिये पहला FieldType। |
| b | [FieldType](../../com.aspose.slides/fieldtype) | तुलना करने के लिये दूसरा FieldType। |

**वापसी:**  
boolean - यदि FieldType ऑब्जेक्ट असमान हों तो true।

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

वर्तमान स्लाइड का क्रमांक। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

स्लाइड का फ़ुटर। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

स्लाइड का हेडर। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

डिफ़ॉल्ट दिनांक-समय प्रारूप में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

पहले निर्धारित प्रारूप (MM/DD/YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

दूसरे निर्धारित प्रारूप (Day, Month DD, YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

तीसरे निर्धारित प्रारूप (DD Month YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

चौथे निर्धारित प्रारूप (Month DD, YYYY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

पांचवें निर्धारित प्रारूप (DD-Mon-YY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

छठे निर्धारित प्रारूप (Month YY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

सातवें निर्धारित प्रारूप (Mon-YY अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

आठवें निर्धारित प्रारूप (MM/DD/YYYY hh:mm AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

नवें निर्धारित प्रारूप (MM/DD/YYYY hh:mm:ss AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

दसवें निर्धारित प्रारूप (hh:mm अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

ग्यारहवें निर्धारित प्रारूप (hh:mm:ss अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

बारहवें निर्धारित प्रारूप (hh:mm AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

तेरहवें निर्धारित प्रारूप (hh:mm:ss AM/PM अंग्रेज़ी के लिए) में वर्तमान दिनांक और समय। पढ़ने-केवल [FieldType](../../com.aspose.slides/fieldtype)।

**वापसी:**  
[FieldType](../../com.aspose.slides/fieldtype)