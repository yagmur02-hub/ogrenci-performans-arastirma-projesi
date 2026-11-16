# Öğrenci Çalışma Süreleri, Devamsızlık ve Akademik Başarı Analizi

**Ders:** Araştırma Yöntem ve Teknikleri / Yazılım Mühendisliği Temelleri (2026-2027 Güz)  
**Öğrenci:** Yağmur Lafcı  
**Araştırma Yöntemi:** Nicel Araştırma — İkincil Açık Veri Analizi (Secondary Data Analysis)

## 1. Araştırma Problemi ve Araştırma Sorusu
- **Problem Durumu:** Öğrencilerin bireysel çalışma süreleri ve okula devamlılık davranışlarının dönem sonu başarı notlarını ne ölçüde açıkladığı, doğrudan anketlerin cevapsızlık yanlılığı riski olmadan doğrulanmış açık veri setleri üzerinden incelenmeye ihtiyaç duymaktadır.
- **Araştırma Sorusu:** Öğrencilerin haftalık ders çalışma süresi ve devamsızlık sayısı ile dönem sonu akademik başarı notu (G3) arasında istatistiksel olarak anlamlı bir ilişki var mıdır ve bu değişkenlerle başarı durumu tahmin edilebilir mi?
- **Hipotezler:**
  - **$H_1$:** Öğrencilerin haftalık ders çalışma süresi arttıkça ve devamsızlık sayısı azaldıkça dönem sonu akademik başarı notu ($G3$) artar.
  - **$H_0$:** Öğrencilerin haftalık ders çalışma süresi ve devamsızlık sayısı ile dönem sonu akademik başarı notu ($G3$) arasında anlamlı bir ilişki yoktur.

## 2. Veri Kaynağı ve Lisans Bilgisi
- **Veri Seti:** UCI Student Performance Dataset
- **Özgün Kaynak:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance) — DOI: `10.24432/C5TG7T`
- **Yazarlar:** Paulo Cortez & Alice Silva (2008), Minho Üniversitesi
- **Lisans:** Creative Commons Attribution 4.0 International (**CC BY 4.0**)

## 3. Depo Klasör Yapısı
- `data/`: Analizde kullanılan CSV (`ogrenci_performans_verisi.csv`) ve JSON (`ogrenci_performans_verisi.json`) veri dosyaları.
- `notebooks/`: Google Colab ortamında çalıştırılan Python veri analizi not defteri (`Hafta6_Ogrenci_Performans_Veri_Analizi.ipynb`).
- `outputs/`: Matplotlib ile üretilen sütun/çizgi grafikleri (`.png`) ve betimsel istatistik özet tabloları (`ozet.csv`, `ozet.json`).
- `docs/uml/`: Araştırma sürecinin Use Case, Class ve Activity UML diyagramları.

## 4. Yapay Zeka Kullanım Beyanı
Bu proje çalışmasında üretken yapay zeka aracından (Google Gemini) araştırma sorusunun yapılandırılması, UML diyagramlarının kurgulanması ve 6. hafta Colab `.ipynb` şablonunun veri setimize uyarlanması aşamalarında yararlanılmıştır. Tüm akademik kaynaklar ve veri seti özgün veri tabanlarından doğrulanmıştır.
