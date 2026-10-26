---
title: AddAfter()
second_title: Aspose.Slides for C++ API संदर्भ
description: सूची में node के बाद element जोड़ता है।
type: docs
weight: 53
url: /hi/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

सूची में **node** के बाद **element** जोड़ता है।

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node जिसे डालना है उसके बाद |
| element | const T\& | Element जोड़ने के लिए |

### वापसी मान

नया node।

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

सूची में **node** के बाद **newNode** जोड़ता है।

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node जिसे डालना है उसके बाद |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | नई node जोड़ने के लिए |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [LinkedListNode](../../linkedlistnode/)
* क्लास [LinkedList](../)
* नामस्थान [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)