---
title: "System::Collections::Generic::Details"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 352
url: /es/system.collections.generic.details/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable utilizado por los métodos de extensión IEnumerable.Cast() y IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable utilizado por el método de extensión IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator utilizado por el método de extensión IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator utilizado por el método de extensión IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator utilizado por el método de extensión IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Estructuras

| Estructura | Descripción |
| --- | --- |
| [ComparerType](./comparertype/) | Compara elementos usando la semántica 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Compara elementos usando la semántica 'less'. |
| [has_method_compareto](./has_method_compareto/) | Comprueba si el método CompareTo existe en el tipo especificado. Si es así, hereda std::true_type, de lo contrario hereda std::false_type. Puede usarse en std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Comprueba si el método CompareTo(SharedPtr<T>) existe en el tipo especificado. Si es así, hereda std::true_type, de lo contrario hereda std::false_type. Puede usarse en std::enable_if. |
| [IsEqualExist](./isequalexist/) | Comprueba si el tipo proporciona el operador ==. |
## Funciones

| Función | Descripción |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Comprueba si el índice está fuera de los límites del contenedor, excluyendo el tamaño del contenedor. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Comprueba si el índice está fuera de los límites del contenedor, excluyendo el tamaño del contenedor. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Comprueba si el índice está fuera de los límites del contenedor, incluyendo el tamaño del contenedor. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Comprueba si el índice está fuera de los límites del contenedor, incluyendo el tamaño del contenedor. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Función auxiliar para determinar si una clase específica tiene el operador ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Función auxiliar para determinar si una clase específica tiene el operador ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Intenta obtener el primer elemento de la colección. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Intenta obtener el primer elemento de la colección que cumple con la función predicado. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Intenta obtener el último elemento de la colección. |
## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Typedef ficticio para comprobar la existencia del operador ==. |