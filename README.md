# TOROOC manifest

TOROOC 제품 Yocto 빌드용 repo manifest.

## C6490P — LIKU FACE LIFT

rubikpi BSP(QLI.1.6 / qim-product-sdk 2.1.1) 기반. meta-torooc / meta-ros / meta-mingw 추가.

```bash
repo init -u git@github.com:torooc/manifest.git -b main -m c6490p-liku-facelift-v1.0.xml
repo sync
```

- `rubikpi-6.6.97-QLI.1.6-Ver.1.3_qim-product-sdk-2.1.1.xml` — rubikpi BSP 원본 manifest (include 대상)
- `c6490p-liku-facelift-v1.0.xml` — 제품 manifest (위를 include + torooc 확장)
