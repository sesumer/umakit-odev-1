# Umakit görev 1 analizi

## 1. İşletim sistem ortam/kurulum yöntemi
- **İşletim Sistemi:** Ubuntu 24.04 LTS
- **Ortam:** Yerel Bilgisayar (Native)
- **Kurulum Notları:** Git ve build-essential paketleri `sudo apt install` komutuyla ve Elif'in yardımlarıyla kuruldu. Sancılı bir süreçti. Elif'in gemini sohbeti olmasa 10 yıl uğraşırdık.

## 2. Karşılaştığım Sorunlar ve Çözümleri
- *Sorun:* İlk başta GitHub'a `push` yaparken kimlik doğrulama hatası aldım.
- *Çözüm:* SSH Key tanımlayarak ve remote URL'i HTTPS yerine SSH olarak ayarlayarak sorunu çözdüm. (Elif'le çözdük yalan söyleyemeyeceğim)

## 3. Terminalden Sistem Bilgisi Çıktısı
Linux ssumer-VirtualBox 6.8.0-138-generic #138~22.04.1-Ubuntu SMP PREEMPT_DYNAMIC Fri Aug  7 13:43:15 UTC  x86_64 x86_64 x86_64 GNU/Linux

