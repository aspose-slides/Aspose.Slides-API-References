---
title: SmartPtr()
second_title: Aspose.Slides for C++ API Reference
description: Creates SmartPtr object of required mode.
type: docs
weight: 1
url: /system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Creates [SmartPtr](../) object of required mode.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Creates null-pointer [SmartPtr](../) object of required mode.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ \*, SmartPtrMode) constructor


Creates [SmartPtr](../) pointing to specified object, or converts raw pointer to [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) \* | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) constructor


Copy constructs [SmartPtr](../) object. Both pointers point to the same object afterwards.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>&, SmartPtrMode) constructor


Copy constructs [SmartPtr](../) object. Both pointers point to the same object afterwards. Performs type conversion if allowed.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type of object pointed by x. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) constructor


Move constructs [SmartPtr](../) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>&, SmartPtrMode) constructor


Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Type of source array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>& | Pointer to array to create a copy of, but with different type of elements. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const Y&) constructor


Initializes empty array. Used to translate some C# code constructs.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>&, Pointee_ \*, SmartPtrMode) constructor


Constructs a [SmartPtr](../) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>& | Another smart pointer to share the ownership to the ownership from. |
| p | [Pointee_](../pointee_/) \* | Pointer to an object to manage. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. <pre><code>#include&nbsp;&quot;system/object.h&quot;<br>#include&nbsp;&quot;system/smart_ptr.h&quot;<br>#include&nbsp;&lt;iostream&gt;<br><br>//&nbsp;This&nbsp;class&nbsp;contains&nbsp;a&nbsp;field&nbsp;that&nbsp;will&nbsp;be&nbsp;printed.<br>class&nbsp;Foo&nbsp;:&nbsp;public&nbsp;System::Object<br>{<br>public:<br>&nbsp;&nbsp;std::string&nbsp;value&nbsp;=&nbsp;&quot;Hello,&nbsp;world!&quot;;<br>};<br><br>//&nbsp;This&nbsp;class&nbsp;contains&nbsp;an&nbsp;instance&nbsp;of&nbsp;the&nbsp;Foo&nbsp;class.<br>class&nbsp;Bar&nbsp;:&nbsp;public&nbsp;System::Object<br>{<br>public:<br>&nbsp;&nbsp;Foo&nbsp;data;<br>};<br><br>//&nbsp;Used&nbsp;to&nbsp;print&nbsp;a&nbsp;string&nbsp;from&nbsp;the&nbsp;Foo-class&nbsp;instance.<br>void&nbsp;PrintMessage(const&nbsp;System::SharedPtr&lt;Foo&gt;&nbsp;&amp;foo)<br>{<br>&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;&nbsp;foo-&gt;value&nbsp;&lt;&lt;&nbsp;std::endl;<br>}<br><br>//&nbsp;Prints&nbsp;the&nbsp;number&nbsp;of&nbsp;shared&nbsp;pointers&nbsp;pointing&nbsp;to&nbsp;the&nbsp;object.<br>void&nbsp;PrintSharedCount(const&nbsp;System::SharedPtr&lt;Bar&gt;&nbsp;&amp;ptr)<br>{<br>&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;&nbsp;&quot;Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;&quot;&nbsp;&lt;&lt;&nbsp;ptr.get_shared_count()&nbsp;&lt;&lt;&nbsp;std::endl;<br>}<br><br>int&nbsp;main()<br>{<br>&nbsp;&nbsp;//&nbsp;Create&nbsp;SharedPtr&nbsp;to&nbsp;an&nbsp;instance&nbsp;of&nbsp;the&nbsp;Bar&nbsp;class.<br>&nbsp;&nbsp;auto&nbsp;bar&nbsp;=&nbsp;System::MakeObject&lt;Bar&gt;();<br>&nbsp;&nbsp;PrintSharedCount(bar);<br>&nbsp;&nbsp;//&nbsp;Create&nbsp;SharedPtr&nbsp;that&nbsp;will&nbsp;point&nbsp;to&nbsp;the&nbsp;field&nbsp;of&nbsp;the&nbsp;Bar-class&nbsp;instance.<br>&nbsp;&nbsp;auto&nbsp;foo&nbsp;=&nbsp;System::SharedPtr&lt;Foo&gt;(bar,&nbsp;&amp;bar-&gt;data);<br>&nbsp;&nbsp;PrintSharedCount(bar);<br><br>&nbsp;&nbsp;//&nbsp;Make&nbsp;the&nbsp;&#39;bar&#39;&nbsp;pointer&nbsp;pointing&nbsp;to&nbsp;nullptr.<br>&nbsp;&nbsp;bar.reset();<br>&nbsp;&nbsp;PrintSharedCount(bar);<br>&nbsp;&nbsp;//&nbsp;bar-&gt;data&nbsp;still&nbsp;exists&nbsp;and&nbsp;the&nbsp;&#39;foo&#39;&nbsp;pointer&nbsp;is&nbsp;valid.<br>&nbsp;&nbsp;PrintMessage(foo);<br><br>&nbsp;&nbsp;return&nbsp;0;<br>}<br>/*<br>This&nbsp;code&nbsp;example&nbsp;produces&nbsp;the&nbsp;following&nbsp;output:<br>Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;1<br>Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;2<br>Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;0<br>Hello,&nbsp;world!<br>*/</code></pre> |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)