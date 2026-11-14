# DUX Structure Visualizer

[Download source code / Kaynak kodu indir](dux-structure-visualizer-source.zip)

Extract the archive before running the commands below. / Aşağıdaki komutları çalıştırmadan önce arşivi açın.

## English

A commodity derivatives simulator for DUX, Double-Up, Parachute and Knock-Out structures. Explore fixing schedules and payoff paths, combine vanilla option legs, and inspect Greeks, volatility and gamma exposure. The trade journal and risk tools use browser-local storage. The GitHub edition includes a synthetic contract example and a local Node.js server.

With Node.js 22 or newer, run `npm run dev` from this directory and open http://127.0.0.1:4173. Run `npm run build` to generate the Worker bundle. Run `node scripts/verify.mjs` and `node scripts/verify-risk.mjs` after building to check calculations and routes. Live settlement availability depends on the ICE endpoint. Gamma exposure is an estimate based on the selected positioning assumptions.

## Türkçe

DUX, Double-Up, Parachute ve Knock-Out yapıları için emtia türevleri simülatörü. Fixing takvimini ve farklı fiyat senaryolarındaki getiriyi inceleyebilir, vanilla opsiyon bacaklarını birleştirebilir, Greeks, volatilite ve gamma maruziyetini görebilirsiniz. İşlem günlüğü ve risk araçları verileri tarayıcıda yerel olarak saklar. GitHub sürümünde sentetik kontrat örneği ve yerel Node.js sunucusu bulunur.

Node.js 22 veya üzeriyle bu klasörde `npm run dev` çalıştırın ve http://127.0.0.1:4173 adresini açın. Worker çıktısını üretmek için `npm run build` çalıştırın. Hesaplamaları ve sayfa yollarını kontrol etmek için derlemeden sonra `node scripts/verify.mjs` ve `node scripts/verify-risk.mjs` komutlarını kullanın. Canlı kapanış verisinin kullanılabilirliği ICE veri kaynağına bağlıdır. Gamma maruziyeti seçilen pozisyonlama varsayımlarına dayalı bir tahmindir.

⚠️ Disclaimer

This project is for educational and engineering research purposes only. It does not constitute financial advice. The developer is not responsible for any financial losses incurred from using this bot or its signals. Trade at your own risk.

⚖️ Yasal Uyarı (Disclaimer)

Bu yazılım tamamen açık kaynaklı bir mühendislik ve veri bilimi araştırma projesi (Proof of Concept) olarak tasarlanmıştır. Çıktıların hiçbiri bir ticaret sistemi teklifi veya finansal yatırım tavsiyesi (YTD) niteliği taşımaz. Finansal piyasalar doğası gereği yüksek risk içerir, projenin kullanımı sonucu doğabilecek kâr veya zararlardan kodun geliştiricileri veya katkıda bulunanlar sorumlu tutulamaz. Yazılımı kullanmadan önce daima kendi risk analizinizi ve testlerinizi gerçekleştirmeniz önerilir.

