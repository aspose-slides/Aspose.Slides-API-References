---
title: CopyTo()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सूची तत्वों को मौजूदा एरे तत्वों में कॉपी करता है।
type: docs
weight: 209
url: /hi/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) विधि


सूची तत्वों को मौजूदा सरणी तत्वों में कॉपी करता है।

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | गंतव्य सरणी। |
| arrayIndex | int | गंतव्य सरणी की प्रारम्भिक इंडेक्स। |

## List::CopyTo(const System::ArrayPtr\<T\>\&) विधि


सभी तत्वों को मौजूदा सरणी तत्वों में कॉपी करता है।

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) में तत्व कॉपी करने के लिए। |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) विधि


निर्दिष्ट इंडेक्स से शुरू करके तत्वों को मौजूदा सरणी तत्वों में कॉपी करता है।

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वर्तमान वस्तु द्वारा प्रस्तुत सूची में 0-आधारित इंडेक्स जिससे कॉपी शुरू करना है |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) में तत्व कॉपी करने के लिए। |
| arrayIndex | int | गंतव्य सरणी में प्रारम्भिक स्थिति। |
| count | int | कॉपी करने के लिए तत्वों की संख्या। |

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)