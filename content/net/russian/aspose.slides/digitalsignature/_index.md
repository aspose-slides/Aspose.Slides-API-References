---
title: DigitalSignature
second_title: Справка по API Aspose.Slides для .NET
description: Цифровая подпись в подписанном файле.
type: docs
weight: 2680
url: /ru/aspose.slides/digitalsignature/
---

## DigitalSignature class

Цифровая подпись в подписанном файле.

```csharp
public class DigitalSignature : IDigitalSignature
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)(X509Certificate2) | Создает новый объект DigitalSignature с указанным сертификатом. |
| [DigitalSignature](digitalsignature#constructor_1)(string, string) | Создает новый объект DigitalSignature с указанным путем к файлу сертификата и паролем. |

## Свойства

| Название | Описание |
| --- | --- |
| [Certificate](../../aspose.slides/digitalsignature/certificate) { get; } | Объект сертификата, который был использован для подписи документа. Только для чтения X509Certificate2. |
| [Comments](../../aspose.slides/digitalsignature/comments) { get; set; } | Цель подписи. Читаемая/записываемая строка. |
| [IsValid](../../aspose.slides/digitalsignature/isvalid) { get; } | Если эта цифровая подпись действительна и документ не был изменен, это значение будет равно true. Только для чтения Boolean. |
| [SignTime](../../aspose.slides/digitalsignature/signtime) { get; } | Время, когда документ был подписан. Только для чтения DateTime. |

### Примеры

Следующий пример демонстрирует, как добавить цифровую подпись из сертификата PFX в презентацию PowerPoint.

```csharp
[C#]
// Инициализация экземпляра Presentation
using (Presentation pres = new Presentation())
{
    // Создание объекта DigitalSignature с файлом PFX и паролем PFX
    DigitalSignature signature = new DigitalSignature("testsignature1.pfx", @"testpass1");
    // Комментарий к новой цифровой подписи
    signature.Comments = "Тест цифровой подписи Aspose.Slides.";
    // Добавление цифровой подписи в презентацию
    pres.DigitalSignatures.Add(signature);
    // Сохранение презентации
    pres.Save("SomePresentationSigned.pptx", SaveFormat.Pptx);
}
```

Следующий образец кода демонстрирует, как проверить цифровую подпись презентации PowerPoint.

```csharp
[C#]
// Инициализация экземпляра Presentation
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    if (pres.DigitalSignatures.Count < 0)
    {
        bool allSignaturesAreValid = true;
        Console.WriteLine("Подписи, использованные для подписания презентации: ");
        // Проверка, являются ли все цифровые подписи действительными
        foreach (DigitalSignature signature in pres.DigitalSignatures)
        {
            Console.WriteLine(signature.Certificate.SubjectName.Name + ", "
                    + signature.SignTime.ToString("yyyy-MM-dd HH:mm") + " -- " + (signature.IsValid ? "ДЕЙСТВИТЕЛЬНА" : "НЕДЕЙСТВИТЕЛЬНА"));
            allSignaturesAreValid &= signature.IsValid;
        }
        if (allSignaturesAreValid)
            Console.WriteLine("Презентация подлинная, все подписи действительны.");
        else
            Console.WriteLine("Презентация была изменена после подписания.");
    }
}
```

### Смотрите также

* интерфейс [IDigitalSignature](../idigitalsignature)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->