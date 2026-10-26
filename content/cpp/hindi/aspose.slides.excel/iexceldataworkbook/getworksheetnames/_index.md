---
title: GetWorksheetNames()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Excel वर्कबुक में शामिल सभी वर्कशीट्स के नाम प्राप्त करता है।
type: docs
weight: 40
url: /hi/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() method

[Excel](../../) वर्कबुक में शामिल सभी वर्कशीट्स के नाम प्राप्त करता है।

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```

### रिटर्न वैल्यू

वर्कशीट नामों की सूची

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IList](../../../system.collections.generic/ilist/)
* क्लास [String](../../../system/string/)
* क्लास [IExcelDataWorkbook](../)
* नेमस्पेस [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)