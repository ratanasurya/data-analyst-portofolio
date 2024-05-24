# Rakamin Virtual Internship - Data Analyst Kimia Farma

## Table :
- kf_final_transaction
- kf_inventory
- kf_kantor_cabang
- kf_product

## ERD :

 ![ERD](https://github.com/ratanasurya/data-analyst-portofolio/assets/158171641/54e611c0-373c-402c-9d3d-8f55402a947b)

## Data Dictionary : 
### kf_final_transaction.csv
   - transaction_id: kode id transaksi,
   - product_id : kode produk obat,
   - branch_id: kode id cabang Kimia Farma,
   - customer_name: nama customer yang melakukan transaksi,
   - date: tanggal transaksi dilakukan,
   - price: harga obat,
   - discount_percentage: Persentase diskon yang diberikan pada obat,
   - rating: penilaian konsumen terhadap transaksi yang dilakukan.
### kf_product.csv
   - product_id: kode produk obat,
   - product_name: nama produk obat,
   - product_category: kategori produk obat,
   - price: harga obat.
### kf_inventory.csv
   - inventory_ID: kode inventory produk obat,
   - branch_id: kode id cabang Kimia Farma,
   - product_id: kode id produk obat,
   - product_name: nama produk obat,
   - opname_stock: jumlah stok produk obat.
### kf_kantor_cabang.csv
   - branch_id: kode id cabang Kimia Farma,
   - branch_category: kategori cabang Kimia Farma,
   - branch_name: nama kantor cabang Kimia Farma,
   - kota: kota cabang Kimia Farma,
   - provinsi: provinsi cabang Kimia Farma,
   - rating: penilaian konsumen terhadap cabang Kimia Farma
