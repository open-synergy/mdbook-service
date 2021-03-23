# Membatalkan Customer Invoice Dari Payment Term

## A. INPUT

* Data **Payment Term** *Service Contract* yang dapat dibatalkan customer invoice harus memiliki status **Invoiced**.

![](../../img/service-contract/output-create-invoice.png)

* User yang akan membatalkan customer invoice harus memiliki akses untuk membatalkan customer invoice *Service Contract*.

## B. LANGKAH KERJA

1. Buka menu **Service -> Service -> Contract**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data *Service Contract* yang akan dibatalkan customer invoice. Abaikan jika data sudah dibuka.
3. Beralih ke tab **[Fix Items](./penjelasan.md#tab-fix-items)**.
4. Klik icon tanda silang pada bagian kanan data **Payment Term** yang akan dibatalkan customer invoice.

![](../../img/service-contract/icon-cancel-invoice.png)

## C. OUTPUT

* Data **Payment Term** *Service Contract* akan berubah menjadi **Uninvoiced**.

![](../../img/service-contract/output-cancel-invoice.png)
