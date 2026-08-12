---
title: ConvertAll()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया Array ऑब्जेक्ट बनाता है और इसे निर्दिष्ट सरणी के तत्वों से भरता है जिन्हें निर्दिष्ट कन्वर्टर डेलीगेट का उपयोग करके OutputType प्रकार में परिवर्तित किया गया है।
type: docs
weight: 625
url: /hi/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) विधि

एक नया [Array](../) ऑब्जेक्ट बनाता है और इसे निर्दिष्ट सरणी के तत्वों से भरता है जो निर्दिष्ट कन्वर्टर डेलीगेट का उपयोग करके **OutputType** प्रकार में परिवर्तित किए गए हैं।

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| InputType | इनपुट सरणी के तत्वों का प्रकार |
| OutputType | परिणामी सरणी के तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | एक [Array](../) ऑब्जेक्ट |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | एक Converter ऑब्जेक्ट जो इनपुट सरणी के प्रत्येक तत्व को **OutputType** प्रकार के समतुल्य मानों में परिवर्तित करने के लिए उपयोग किया जाता है |

### रिटर्न मान

एक नई सरणी जिसमें **OutputType** प्रकार के मान हैं जो **input_array** के मानों के समतुल्य हैं।

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) विधि

एक नया [Array](../) ऑब्जेक्ट बनाता है और इसे निर्धारित सरणी के तत्वों से भरता है जो निर्दिष्ट कन्वर्टर फ़ंक्शन ऑब्जेक्ट का उपयोग करके **OutputType** प्रकार में परिवर्तित किए गए हैं।

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| InputType | इनपुट सरणी के तत्वों का प्रकार |
| OutputType | परिणामी सरणी के तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | एक [Array](../) ऑब्जेक्ट |
| converter | std::function\<OutputType(InputType)> | एक फ़ंक्शन ऑब्जेक्ट जो इनपुट सरणी के प्रत्येक तत्व को **OutputType** प्रकार के समतुल्य मानों में परिवर्तित करने के लिए उपयोग किया जाता है |

### रिटर्न मान

एक नई सरणी जिसमें **OutputType** प्रकार के मान हैं जो **input_array** के मानों के समतुल्य हैं।

## देखें भी

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)