---
title: set_Mode()
second_title: Aspose.Slides for C++ API Reference
description: Sets pointer mode. May alter referenced object's reference counts.
type: docs
weight: 183
url: /system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) method


Sets pointer mode. May alter referenced object's reference counts.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | New mode of pointer. <pre><code>#include&nbsp;&quot;system/smart_ptr.h&quot;<br>#include&nbsp;&lt;iostream&gt;<br><br>class&nbsp;Item&nbsp;final&nbsp;:&nbsp;public&nbsp;System::Object<br>{<br>public:<br>&nbsp;&nbsp;~Item()&nbsp;final<br>&nbsp;&nbsp;{<br>&nbsp;&nbsp;&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;&nbsp;&quot;~Item()&quot;&nbsp;&lt;&lt;&nbsp;std::endl;<br>&nbsp;&nbsp;}<br>};<br><br>using&nbsp;ItemPtr&nbsp;=&nbsp;System::SmartPtr&lt;Item&gt;;<br><br>void&nbsp;PrintSharedCount(ItemPtr&nbsp;&amp;ptr)<br>{<br>&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;&nbsp;&quot;Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;&quot;&nbsp;&lt;&lt;&nbsp;ptr.get_shared_count()&nbsp;&lt;&lt;&nbsp;std::endl;<br>}<br><br>void&nbsp;ChangeModeToWeak(ItemPtr&nbsp;&amp;ptr)<br>{<br>&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;&nbsp;&quot;The&nbsp;mode&nbsp;will&nbsp;be&nbsp;changed&nbsp;to&nbsp;System::SmartPtrMode::Weak&quot;&nbsp;&lt;&lt;&nbsp;std::endl;<br>&nbsp;&nbsp;ptr.set_Mode(System::SmartPtrMode::Weak);<br>&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;&nbsp;&quot;The&nbsp;mode&nbsp;has&nbsp;been&nbsp;changed&nbsp;to&nbsp;System::SmartPtrMode::Weak&quot;&nbsp;&lt;&lt;&nbsp;std::endl;<br>}<br><br>int&nbsp;main()<br>{<br>&nbsp;&nbsp;ItemPtr&nbsp;ptr1&nbsp;=&nbsp;System::MakeObject&lt;Item&gt;();<br>&nbsp;&nbsp;ItemPtr&nbsp;ptr2{ptr1,&nbsp;System::SmartPtrMode::Weak};<br>&nbsp;&nbsp;PrintSharedCount(ptr1);<br><br>&nbsp;&nbsp;ptr2.set_Mode(System::SmartPtrMode::Shared);<br>&nbsp;&nbsp;PrintSharedCount(ptr1);<br><br>&nbsp;&nbsp;ChangeModeToWeak(ptr1);<br>&nbsp;&nbsp;ChangeModeToWeak(ptr2);<br>&nbsp;&nbsp;std::cout&nbsp;&lt;&lt;<br>&nbsp;&nbsp;&nbsp;&nbsp;&quot;The&nbsp;pointer&nbsp;to&nbsp;an&nbsp;instance&nbsp;of&nbsp;the&nbsp;Item&nbsp;class&nbsp;expired:&nbsp;&quot;&nbsp;&lt;&lt;<br>&nbsp;&nbsp;&nbsp;&nbsp;(static_cast&lt;System::WeakPtr&lt;ItemPtr::Pointee_&gt;&gt;(ptr1).expired()&nbsp;?&nbsp;&quot;True&quot;&nbsp;:&nbsp;&quot;False&quot;)&nbsp;&lt;&lt;<br>&nbsp;&nbsp;&nbsp;&nbsp;std::endl;<br><br>&nbsp;&nbsp;return&nbsp;0;<br>}<br>/*<br>This&nbsp;code&nbsp;example&nbsp;produces&nbsp;the&nbsp;following&nbsp;output:<br>Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;1<br>Number&nbsp;of&nbsp;shared&nbsp;pointers:&nbsp;2<br>The&nbsp;mode&nbsp;will&nbsp;be&nbsp;changed&nbsp;to&nbsp;System::SmartPtrMode::Weak<br>The&nbsp;mode&nbsp;has&nbsp;been&nbsp;changed&nbsp;to&nbsp;System::SmartPtrMode::Weak<br>The&nbsp;mode&nbsp;will&nbsp;be&nbsp;changed&nbsp;to&nbsp;System::SmartPtrMode::Weak<br>~Item()<br>The&nbsp;mode&nbsp;has&nbsp;been&nbsp;changed&nbsp;to&nbsp;System::SmartPtrMode::Weak<br>The&nbsp;pointer&nbsp;to&nbsp;an&nbsp;instance&nbsp;of&nbsp;the&nbsp;Item&nbsp;class&nbsp;expired:&nbsp;True<br>*/</code></pre> |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)