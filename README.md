🛡️ تحليل البيانات الوصفية للكشف عن التزوير
🛡️ Project: Metadata Analysis for Fraud Detection
📄 الوصف | Description
يهدف هذا المشروع الأكاديمي إلى استخدام تحليل البيانات الوصفية (Metadata Analysis) في مجال الأدلى بيلسيم (Digital Forensics) للكشف عن التزوير أو الوصول غير المصرح به إلى الملفات الرقمية.
تم إجراء التحليل على بيانات مُصدَّرة من Google Takeout (تحتوي على 502 ملف متنوع مثل PDF وDOCX وJPEG)، باستخدام أدوات مثل ExifTool لاستخراج البيانات الوصفية، وخوارزمية Isolation Forest لاكتشاف الشذوذات.

This academic project focuses on applying Metadata Analysis in Digital Forensics to detect fraud or unauthorized access to digital files.
The analysis was performed on data exported from Google Takeout (502 diverse files including PDF, DOCX, and JPEG) using tools like ExifTool for metadata extraction and Isolation Forest for anomaly detection.

🎯 الأهداف الرئيسية | Main Objectives
استخراج معلومات وصفية مثل (تاريخ الإنشاء، تاريخ التعديل، المؤلف، الموقع الجغرافي).

اكتشاف الملفات التي قد تحتوي على علامات تزوير أو تعديل غير مصرح به باستخدام خوارزميات تعلم آلي.

تقديم توصيات لتحسين جمع البيانات وتحليلها في مجال الأدلى بيلسيم.

Extract metadata (e.g., creation date, modification date, author, geographic location).

Detect files that may show signs of fraud or unauthorized modification using machine learning algorithms.

Provide recommendations to improve data collection and analysis in digital forensics.


📦 المحتويات | Contents
adli_bilisim_raporu.tex – نص المقالة الأكاديمية مكتوب بـ LaTeX.

images/ – مجلد يحوي رسومًا بيانية وصورًا لدعم النتائج.

adlibilişim.py – سكربت بايثون (لتحليل البيانات أو اكتشاف الشذوذات).

ملفات بيانات إضافية (إن وُجدت).

adli_bilisim_raporu.tex – Academic paper written in LaTeX.

images/ – Folder with graphs and images supporting the results.

adlibilişim.py – Python script (for data analysis or anomaly detection).

Additional data files (if any).

📊 النتائج الرئيسية | Key Findings
تم تحليل 502 ملفًا، وكُشف عن 51 ملفًا شاذًا (10.16%).

8 ملفات حصلت على درجات مخاطر عالية (>80) تُشير لاحتمال وجود تزوير.

معدل البيانات الناقصة كان مرتفعًا (مثل 23.51% لتاريخ الإنشاء)، مما يعكس الحاجة لتحسين عمليات الجمع.

502 files analyzed, with 51 anomalies detected (10.16%).

8 files had high risk scores (>80), indicating potential fraud.

Missing data rate was high (e.g., 23.51% for creation date), suggesting better data collection is needed.

⚙️ كيفية الاستخدام | How to Use

# استنساخ المستودع | Clone the repository
git clone https://github.com/muhammed-neccar/Muhammed-Neccar-AdliBilisim.git

# الانتقال إلى المجلد | Navigate into the folder
cd Muhammed-Neccar-AdliBilisim

# التأكد من تثبيت التبعيات | Make sure dependencies are installed
# Python, pandas, scikit-learn, ExifTool

# تشغيل التحليل | Run the analysis
python adlibilişim.py

# توليد المقالة بصيغة PDF | Compile the paper to PDF
# باستخدام Overleaf أو LaTeX محلي

🗓️ تاريخ الإصدار | Release Date
3 يوليو 2025 | July 03, 2025

📜 الترخيص | License
هذا المشروع مرخص بموجب MIT. راجع ملف LICENSE للتفاصيل.
This project is licensed under the MIT License. See the LICENSE file for details.

💡 ملاحظات إضافية | Additional Notes
المشروع مفتوح للمساهمات! إذا كنت ترغب في تحسين التحليل أو إضافة أدوات جديدة، يرجى فتح Issue أو إرسال Pull Request.

تفاصيل إضافية وشرح موسع متاحة في المقالة الأكاديمية المرفقة.




