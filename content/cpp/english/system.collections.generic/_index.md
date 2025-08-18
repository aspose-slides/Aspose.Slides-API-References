---
title: "System::Collections::Generic"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 326
url: /system.collections.generic/
---



## Classes

| Class | Description |
| --- | --- |
| [_KeyCollection](./_keycollection/) | Collection of [Dictionary](./dictionary/)'s keys. References collection, doesn't copy anything. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [_KeyList](./_keylist/) | Implements list of dictionary's keys. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [_ValueCollection](./_valuecollection/) | Collection of [Dictionary](./dictionary/)'s values. References collection, doesn't copy anything. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [_ValueList](./_valuelist/) | Implements list of dictionary's values. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BaseDictionary](./basedictionary/) | Implements common code for various dictionary-alike data structures (e. g. [Dictionary](./dictionary/), [SortedDictionary](./sorteddictionary/)). Shouldn't be used directly, except for inheritance when defining containers. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BaseEnumerator](./baseenumerator/) | Enumerator definition to wrap STL-styled types for C#-styled usage. Makes no assertions on container structure except for existance of sequental iterator. Uses begin() and end() functions. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BaseKVCollection](./basekvcollection/) | Holds common code for collections of keys or values. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | Provides a base class for implementations of the [System.Collections.Generic.IComparer](./icomparer/) generic interface. |
| [DefaultComparer](./defaultcomparer/) | Default comparator class. Uses operator < and operator == to compare values. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | Forward declaration of [Dictionary](./dictionary/) class. |
| [DictionaryIterator](./dictionaryiterator/) | [Dictionary](./dictionary/) iterator that provides [KeyValuePair](./keyvaluepair/) notation. |
| [DictionaryPtr](./dictionaryptr/) | [Dictionary](./dictionary/) pointer class with operator overloads. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | Iterator that wraps the pre-created enumerator and redirects all calls into it. |
| [HashDictionary](./hashdictionary/) | Stub for [HashDictionary](./hashdictionary/) class (not implemented currently). Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HashSet](./hashset/) | Forward declaration of [HashSet](./hashset/) class. |
| [HashSetPtr](./hashsetptr/) | Pointer to keep [HashSet](./hashset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [ICollection](./icollection/) | Interface of collection of elements. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IComparer](./icomparer/) | Interface that compares two objects in greater-equal-less sense. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IDictionary](./idictionary/) | Interface for dictionary-alike containers. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IEnumerable](./ienumerable/) | Interface of object providing enumerator on contained elements. |
| [IEnumerator](./ienumerator/) | Interface of enumerator which can be used to iterate through some elements. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IEqualityComparer](./iequalitycomparer/) | Interface providing means to compare two objects for equality. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IKVCollection](./ikvcollection/) | Interface of container containing keys or values of the dictionary-like container. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IList](./ilist/) | Interface of indexed container of elements. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ISet](./iset/) | Interface of collection containing a set of unique elements. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [KeyIterator](./keyiterator/) | [Dictionary](./dictionary/) iterator that provides key access. |
| [KeyValuePair](./keyvaluepair/) | Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../system/smartptr/) class to manage objects of this type. |
| [KVPairIterator](./kvpairiterator/) | Adapting iterator, wraps std::pair into KVPair expected from [Dictionary](./dictionary/). |
| [LinkedList](./linkedlist/) | [LinkedList](./linkedlist/) forward declaration. |
| [LinkedListNode](./linkedlistnode/) | Node of linked list. Implements a wrapper over an iterator of std::list that is wrapped in linked list. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [List](./list/) | [List](./list/) forward declaration. |
| [ListExt](./listext/) | generic [List](./list/) class that implements [IListWrapper](../system.collections/ilistwrapper/) interface |
| [ListPtr](./listptr/) | [List](./list/) pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [Queue](./queue/) | [Queue](./queue/) class forward declaration. |
| [QueuePtr](./queueptr/) | [Queue](./queue/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [ReverseEnumerator](./reverseenumerator/) | Enumerator that reverse-iterates through container. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SimpleEnumerator](./simpleenumerator/) | Iterator class for simple containers holding elements directly using rbegin() and rend() functions. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SortedDictionary](./sorteddictionary/) | Sorted dictionary type forward declaration. |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | Sorted dictionary pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [SortedList](./sortedlist/) | Sorted list wrapping FlatMap structure. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SortedListHelper](./sortedlisthelper/) | This helper class is used to mask virtual functions get_Keys get_Values that come from [IDictionary](./idictionary/) interface and substitute these to the functions with different return type. |
| [SortedSet](./sortedset/) | Forward declaration of [SortedSet](./sortedset/) class. |
| [SortedSetPtr](./sortedsetptr/) | Pointer to keep [SortedSet](./sortedset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [Stack](./stack/) | [Stack](./stack/) class forward declaration. |
| [StackPtr](./stackptr/) | [Stack](./stack/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [ValueIterator](./valueiterator/) | [Dictionary](./dictionary/) iterator that provides value access. |
## Structures

| Struct | Description |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | Adapter to use [IComparer](./icomparer/) within STL environment. Uses [IComparer](./icomparer/) if set; otherwise, uses operator < (if available) or returns false (if not). |
| [DictionaryHashSelector](./dictionaryhashselector/) | Hash function selector for [Dictionary](./dictionary/) class. This implementation uses STL hashing given no alternative is provided. |
| [EqualityComparerAdapter](./equalitycompareradapter/) | Adapter making it possible using [IEqualityComparer](./iequalitycomparer/) with STL-styled collections and algorithms. Uses [IEqualityComparer](./iequalitycomparer/), if set. If not set, uses operator ==, [Object::Equals](../system/object/equals/) or T::Equals, whichever is available. |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | Adapter to use [IEqualityComparer](./iequalitycomparer/) for hashing. Uses comparator object, if set; otherwise, uses available hash method selected using [DictionaryHashSelector](./dictionaryhashselector/) struct. |
## Functions

| Function | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Compares two key-value pairs using 'equals' semantics. Uses operator == or EqualsTo method for both keys and values, whichever is defined. |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Compares two key-value pairs using inverse 'equals' semantics. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Insert data into the stream using UTF-8 encoding. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Insert data into the stream. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |
