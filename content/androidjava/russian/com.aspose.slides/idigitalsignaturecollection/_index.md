---
title: IDigitalSignatureCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию цифровых подписей, прикреплённых к документу.
type: docs
url: /ru/com.aspose.slides/idigitalsignaturecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Представляет коллекцию цифровых подписей, прикреплённых к документу.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает подпись по индексу. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Добавляет подпись в конец коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет подпись по указанному индексу. |
| [clear()](#clear--) | Удаляет все подписи из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Возвращает подпись по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Добавляет подпись в конец коллекции.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Подпись для добавления. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет подпись по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс подписи, которую следует удалить. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все подписи из коллекции.