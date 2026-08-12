---
title: operator-()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दो सप्ताह के दिनों के बीच दिनों की संख्या की गणना करता है।
type: docs
weight: 2172
url: /hi/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) फ़ंक्शन


दो सप्ताह के दिनों के बीच दिनों की संख्या की गणना करता है।

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | घटाने वाला |
| b | [DayOfWeek](../dayofweek/) | घटाया गया |

### रिटर्न मान

सप्ताह के दिनों **a** और **b** के बीच दिनों की संख्या; यदि *जाता है* के बाद **** तो रिटर्न मान नकारात्मक संख्या होगा।

## System::operator-(const T\&, const Decimal\&) फ़ंक्शन


एक नया [Decimal](../decimal/) क्लास की इंस्टेंस लौटाता है जो उन मान को दर्शाता है जो निर्दिष्ट [Decimal](../decimal/) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान को निर्दिष्ट मान से घटाने के परिणाम के रूप में प्राप्त होता है।

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const T\& | वह मान जिससे घटाया जाना है |
| d | const [Decimal](../decimal/)\& | घटाए गए मान का प्रतिनिधित्व करने वाला [Decimal](../decimal/) ऑब्जेक्ट |

### रिटर्न मान

एक नया [Decimal](../decimal/) क्लास का इंस्टेंस जो उस मान को दर्शाता है जो **d** द्वारा प्रतिनिधित्व किए गए मान को **x** से घटाने के परिणाम के रूप में प्राप्त होता है।

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) फ़ंक्शन


बाएँ हाथ के डेलीगेट कॉलबैक सूची के अंत से दाएँ हाथ के डेलीगेट के सभी कॉलबैक को डिस्कनेक्ट करता है।

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | वह डेलीगेट जिससे कॉलबैक हटाए जाएंगे। |
| rhv | MulticastDelegate\<T\> | वह डेलीगेट जिसके कॉलबैक हटाए जाएंगे। |

### रिटर्न मान

एक डेलीगेट लौटाता है जिसमें बाएँ हाथ के मान के कॉलबैक होते हैं, लेकिन दाएँ हाथ के मान के कॉलबैक नहीं होते।

## System::operator-(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन


नॉन-नल और नल योग्य मानों को घटाता है।

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | बाएँ ऑपेरेंड प्रकार। |
| T2 | दाएँ ऑपेरेंड प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | बाएँ ऑपेरेंड। |
| other | const [Nullable](../nullable/)\<T2\>\& | दाएँ ऑपेरेंड। |

### रिटर्न मान

घटाव परिणाम।

## देखें

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)