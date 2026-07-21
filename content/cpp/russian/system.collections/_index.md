---
title: "System::Collections"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 300
url: /ru/system.collections/
---
## Classes

| Class | Description |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) битов, которые могут быть адресованы по индексу. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [BitArrayPtr](./bitarrayptr/) | Указатель на [BitArray](./bitarray/). Этот тип представляет собой указатель для управления удалением других объектов. Он должен быть выделен в стеке и передан в функции либо по значению, либо по константной ссылке. |
| [CollectionBase](./collectionbase/) | Предоставляет абстрактный базовый класс для строго типизированной коллекции. |
| [ICollection](./icollection/) | Определяет интерфейс необобщённой коллекции. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) — базовый интерфейс для всех негенерических коллекций, которые могут быть перечислены. |
| [IEnumerator](./ienumerator/) | Интерфейс перечислителя, который может использоваться для итерации по некоторым элементам. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Обёртка, создающая необобщённую реализацию [IEnumerator](./ienumerator/) поверх обобщённого Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) — обёртка для ссылочных типов. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Обёртка, создающая необобщённую реализацию [IEnumerator](./ienumerator/) поверх обобщённого Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) — обёртка для типов-значений. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) представляет собой негенерическую коллекцию объектов, к которым можно индивидуально обратиться по индексу. |
| [IListImplRefType](./ilistimplreftype/) | Заглушка, реализующая интерфейс [System::Collections::IList](./ilist/) на объекте [System::Collections::Generic::List](../system.collections.generic/list/). Реализация для ссылочных типов. |
| [IListImplValueType](./ilistimplvaluetype/) | Заглушка, реализующая интерфейс [System::Collections::IList](./ilist/) на объекте [System::Collections::Generic::List](../system.collections.generic/list/). Реализация для типов-значений. |
| [IListWrapper](./ilistwrapper/) | Интерфейс для поддержки приведения из обобщённой коллекции в негенерическую. |
| [Invalidatable](./invalidatable/) | Класс, позволяющий отслеживать состояние своих потомков через объекты [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Класс, реализующий трекеры объектов [Invalidatable](./invalidatable/). |