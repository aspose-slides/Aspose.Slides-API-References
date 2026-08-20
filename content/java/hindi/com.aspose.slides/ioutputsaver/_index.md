---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: एक आउटपुट सहेजने वाली सेवा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

एक आउटपुट सहेजने वाली सेवा का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | आउटपुट फ़ाइल को दिए गए पथ पर सहेजता है। |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

आउटपुट फ़ाइल को दिए गए पथ पर सहेजता है।

--------------------

> ```
> Saving into the FileStream implementation example:
>  
>  public void save(String path, IOutputFile outputFile)
>  {
>      FileOutputStream stream = new FileOutputStream(path);
>      try {
>          outputFile.write(stream);
>      } catch (IOException e) {
>      } finally {
>          if (stream != null) stream.close();
>      }
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | फ़ाइल को सहेजने के लिए पथ। |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | आउटपुट फ़ाइल। |