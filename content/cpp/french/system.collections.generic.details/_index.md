---
title: "System::Collections::Generic::Details"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 352
url: /fr/system.collections.generic.details/
---
## Classes

| Classe | Description |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable utilisé par les méthodes d'extension IEnumerable.Cast() et IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable utilisé par la méthode d'extension IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Énumérateur utilisé par la méthode d'extension IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Énumérateur utilisé par la méthode d'extension IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Énumérateur utilisé par la méthode d'extension IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Structures

| Structure | Description |
| --- | --- |
| [ComparerType](./comparertype/) | Compare les éléments en utilisant la sémantique 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Compare les éléments en utilisant la sémantique 'less'. |
| [has_method_compareto](./has_method_compareto/) | Vérifie si la méthode CompareTo existe dans le type spécifié. Si c'est le cas, hérite de std::true_type, sinon hérite de std::false_type. Peut être utilisé dans std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Vérifie si la méthode CompareTo(SharedPtr<T>) existe dans le type spécifié. Si c'est le cas, hérite de std::true_type, sinon hérite de std::false_type. Peut être utilisé dans std::enable_if. |
| [IsEqualExist](./isequalexist/) | Vérifie si le type fournit l'opérateur ==. |
## Fonctions

| Fonction | Description |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Vérifie si l'index est hors des limites du conteneur, en excluant la taille du conteneur. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Vérifie si l'index est hors des limites du conteneur, en excluant la taille du conteneur. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Vérifie si l'index est hors des limites du conteneur, en incluant la taille du conteneur. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Vérifie si l'index est hors des limites du conteneur, en incluant la taille du conteneur. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Fonction d'aide pour déterminer si une classe spécifique possède l'opérateur ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Fonction d'aide pour déterminer si une classe spécifique possède l'opérateur ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Tente d'obtenir le premier élément de la collection. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Tente d'obtenir le premier élément de la collection qui satisfait la fonction prédicat. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Tente d'obtenir le dernier élément de la collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Typedef factice pour vérifier l'existence de l'opérateur ==. |