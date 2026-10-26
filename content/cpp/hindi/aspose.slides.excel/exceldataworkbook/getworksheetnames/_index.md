---
title: GetWorksheetNames()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Excel वर्कबुक में शामिल सभी वर्कशीटों के नाम प्राप्त करता है।
type: docs
weight: 53
url: /hi/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() विधि

सभी वर्कशीट के नाम प्राप्त करता है जो [Excel](../../) वर्कबुक में शामिल हैं।

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```

### रिटर्न वैल्यू

वर्कशीट नामों की सूची

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IList](../../../system.collections.generic/ilist/)
* क्लास [String](../../../system/string/)
* क्लास [ExcelDataWorkbook](../)
* नेमस्पेस [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)