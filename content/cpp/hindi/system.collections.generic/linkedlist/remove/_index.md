---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट तत्व की पहली उपस्थिति को सूची से हटाता है।
type: docs
weight: 196
url: /hi/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) मेथड

निर्दिष्ट **element** की पहली उपस्थिति को सूची से हटाता है।

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | const T\& | हटाने के लिये तत्व। |

### वापसी मान

यदि **element** मिला और हटाया गया तो True, अन्यथा false।

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) मेथड

सूची से नोड हटाता है।

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | हटाने के लिये नोड। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [LinkedList](../)
* क्लास [LinkedListNode](../../linkedlistnode/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)