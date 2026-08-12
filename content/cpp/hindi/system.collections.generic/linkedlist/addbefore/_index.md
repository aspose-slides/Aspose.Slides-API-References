---
title: AddBefore()
second_title: Aspose.Slides for C++ API संदर्भ
description: सूची में नोड से पहले तत्व जोड़ता है।
type: docs
weight: 66
url: /hi/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) विधि

सूची में **node** से पहले **element** जोड़ता है।

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | डालने के लिए नोड |
| element | const T\& | जोड़ने के लिए तत्व |

### रिटर्न मान

नया नोड।

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) विधि

सूची में **node** से पहले **newNode** जोड़ता है।

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | डालने के लिए नोड |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | जोड़ने के लिए नया नोड |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [LinkedListNode](../../linkedlistnode/)
* क्लास [LinkedList](../)
* नेमस्पेस [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)