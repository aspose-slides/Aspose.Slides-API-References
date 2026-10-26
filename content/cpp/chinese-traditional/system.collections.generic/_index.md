---
title: "System::Collections::Generic"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 326
url: /zh-hant/system.collections.generic/
---
## 類別

| Class | 說明 |
| --- | --- |
| [_KeyCollection](./_keycollection/) | [Dictionary](./dictionary/) 的鍵集合。引用集合，不會複製任何內容。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [_KeyList](./_keylist/) | 實作字典鍵的列表。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [_ValueCollection](./_valuecollection/) | [Dictionary](./dictionary/) 的值集合。引用集合，不會複製任何內容。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [_ValueList](./_valuelist/) | 實作字典值的列表。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BaseDictionary](./basedictionary/) | 為各種類似字典的資料結構（例如 [Dictionary](./dictionary/)、[SortedDictionary](./sorteddictionary/)）實作通用程式碼。除非在定義容器時作為基底繼承，否則不應直接使用。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BaseEnumerator](./baseenumerator/) | 列舉器定義，用於將 STL 風格的型別包裝成 C# 風格的使用方式。除檢查是否存在序列化迭代器外，對容器結構不做任何斷言。使用 begin() 和 end() 函式。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BaseKVCollection](./basekvcollection/) | 保存鍵或值集合的通用程式碼。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | 提供 [System.Collections.Generic.IComparer](./icomparer/) 泛型介面的實作基礎類別。 |
| [DefaultComparer](./defaultcomparer/) | 預設比較器類別。使用 operator < 與 operator == 來比較值。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | [Dictionary](./dictionary/) 類別的前置宣告。 |
| [DictionaryIterator](./dictionaryiterator/) | [Dictionary](./dictionary/) 迭代器，提供 [KeyValuePair](./keyvaluepair/) 標記法。 |
| [DictionaryPtr](./dictionaryptr/) | [Dictionary](./dictionary/) 指標類別，具備運算子重載。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | 迭代器，包裝預先建立的列舉器，並將所有呼叫重新導向至該列舉器。 |
| [HashDictionary](./hashdictionary/) | [HashDictionary](./hashdictionary/) 類別的存根（目前未實作）。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [HashSet](./hashset/) | [HashSet](./hashset/) 類別的前置宣告。 |
| [HashSetPtr](./hashsetptr/) | [HashSet](./hashset/) 參考的指標。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [ICollection](./icollection/) | 元素集合的介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [IComparer](./icomparer/) | 比較兩個物件之大於、等於、小於關係的介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [IDictionary](./idictionary/) | 類似字典容器的介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [IEnumerable](./ienumerable/) | 提供包含元素列舉器之物件的介面。 |
| [IEnumerator](./ienumerator/) | 可用於遍歷某些元素之列舉器介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [IEqualityComparer](./iequalitycomparer/) | 提供比較兩個物件相等性的介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [IKVCollection](./ikvcollection/) | 包含字典類似容器之鍵或值的容器介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [IList](./ilist/) | 元素索引容器的介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [ISet](./iset/) | 包含唯一元素集合的容器介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [KeyIterator](./keyiterator/) | [Dictionary](./dictionary/) 迭代器，提供鍵存取。 |
| [KeyValuePair](./keyvaluepair/) | 鍵值對。此型別應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](../system/smartptr/) 類別來管理此型別的物件。 |
| [KVPairIterator](./kvpairiterator/) | 適配迭代器，將 std::pair 包裝成 [Dictionary](./dictionary/) 所期望的 KVPair。 |
| [LinkedList](./linkedlist/) | [LinkedList](./linkedlist/) 前置宣告。 |
| [LinkedListNode](./linkedlistnode/) | 連結串列的節點。實作對 std::list 迭代器之包裝，該迭代器被包在連結串列中。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [List](./list/) | [List](./list/) 前置宣告。 |
| [ListExt](./listext/) | 通用 [List](./list/) 類別，實作 [IListWrapper](../system.collections/ilistwrapper/) 介面。 |
| [ListPtr](./listptr/) | [List](./list/) 指標，具備存取運算子。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [Queue](./queue/) | [Queue](./queue/) 類別前置宣告。 |
| [QueuePtr](./queueptr/) | [Queue](./queue/) 指標。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [ReverseEnumerator](./reverseenumerator/) | 反向遍歷容器的列舉器。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [SimpleEnumerator](./simpleenumerator/) | 簡單容器的迭代器類別，直接使用 rbegin() 與 rend() 函式持有元素。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [SortedDictionary](./sorteddictionary/) | 已排序字典型別的前置宣告。 |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | 已排序字典指標，具備存取運算子。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [SortedList](./sortedlist/) | 包裝 FlatMap 結構的已排序清單。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [SortedListHelper](./sortedlisthelper/) | 此輔助類別用於隱蔽來自 [IDictionary](./idictionary/) 介面的虛擬函式 get_Keys、get_Values，並將其替換為回傳型別不同的函式。 |
| [SortedSet](./sortedset/) | [SortedSet](./sortedset/) 類別的前置宣告。 |
| [SortedSetPtr](./sortedsetptr/) | [SortedSet](./sortedset/) 參考的指標。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [Stack](./stack/) | [Stack](./stack/) 類別前置宣告。 |
| [StackPtr](./stackptr/) | [Stack](./stack/) 指標。此型別用於管理其他物件的刪除。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [ValueIterator](./valueiterator/) | [Dictionary](./dictionary/) 迭代器，提供值存取。 |

## 結構

| Struct | 說明 |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | 適配器，用於在 STL 環境中使用 [IComparer](./icomparer/)。若設定 [IComparer](./icomparer/)，則使用之；否則使用 operator <（如果可用）或返回 false（如果不可用）。 |
| [DictionaryHashSelector](./dictionaryhashselector/) | [Dictionary](./dictionary/) 類別的雜湊函式選擇器。若未提供替代方案，此實作使用 STL 雜湊。 |
| [EqualityComparerAdapter](./equalitycompareradapter/) | 適配器，使 [IEqualityComparer](./iequalitycomparer/) 能與 STL 風格的集合與演算法一起使用。若設定 [IEqualityComparer](./iequalitycomparer/)，則使用之；若未設定，則使用 operator ==、[Object::Equals](../system/object/equals/) 或 T::Equals，以可用者為准。 |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | 適配器，用於使用 [IEqualityComparer](./iequalitycomparer/) 進行雜湊。若設定比較器物件，則使用之；否則使用由 [DictionaryHashSelector](./dictionaryhashselector/) 結構選擇的可用雜湊方法。 |

## 函式

| 函式 | 說明 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 比較兩個鍵值對，使用「equals」語意。對鍵和值皆使用 operator == 或 EqualsTo 方法（視哪個已定義而定）。 |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 使用相反的「equals」語意比較兩個鍵值對。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 將資料插入串流。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |