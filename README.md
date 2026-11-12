# flowchart-memeriksa-payung
Flowchart memeriksa payung sebelum berangkat sekolah atau kerja
```mermaid
flowchart TD
    A([Mulai]) --> B[Periksa kondisi cuaca]
    B --> C{Apakah berpotensi hujan?}
    C -->|Ya| D[Ambil payung]
    C -->|Tidak| E[Siapkan perlengkapan]
    D --> F{Apakah payung dalam kondisi baik?}
    F -->|Ya| G[Masukkan payung ke tas]
    F -->|Tidak| H[Gunakan payung cadangan]
    H --> G
    G --> E
    E --> I[Berangkat ke sekolah/kerja]
    I --> J([Selesai])
