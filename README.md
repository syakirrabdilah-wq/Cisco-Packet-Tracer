# Cisco-Packet-Tracer
This is the network topology design that I made

# Enterprise Multi-Branch Network Simulation

![simulasi_jaringan_multi-branch.png]() <!-- Ganti dengan screenshot topologi keseluruhan nantinya -->

## 📌 Project Overview
Project ini adalah simulasi infrastruktur jaringan berskala enterprise yang menghubungkan empat kantor cabang: **Jakarta, Bandung, Tegal, dan Bali**. Simulasi ini dirancang menggunakan Cisco Packet Tracer dan mendemonstrasikan implementasi *routing* antar wilayah serta pengamanan jaringan menggunakan *Access Control List* (ACL).

**Main Project File:** `simulasi_jaringan_multi-branch.pkt`

## ⚙️ Key Technologies & Protocols
*   **Topology Design:** Hierarchical/Multi-branch network design.
*   **IP Addressing:** Variable Length Subnet Mask (VLSM) untuk efisiensi alokasi IP di setiap cabang.
*   **Routing:** Static Routing diimplementasikan pada seluruh *router* cabang untuk memastikan konektivitas *end-to-end* (lihat contoh `konfigurasi_routing_pada_router_jakarta.jpg`).
*   **Security:** Extended Access Control List (ACL) dikonfigurasi untuk membatasi *traffic* spesifik antar *subnet* dan mengamankan jaringan internal masing-masing cabang.

## 🗂️ Repository Structure
```text
📦 multi-branch-network
 ┣ 📂 konfigurasi                    # Dokumentasi screenshot konfigurasi dan topologi
 ┃ ┣ 🖼️ konfigurasi_ACL_pada_router_bali.jpg
 ┃ ┣ 🖼️ konfigurasi_ACL_pada_router_bandung.jpg
 ┃ ┣ 🖼️ konfigurasi_ACL_pada_router_jakarta.jpg
 ┃ ┣ 🖼️ konfigurasi_ACL_pada_router_tegal.jpg
 ┃ ┣ 🖼️ konfigurasi_routing_pada_router_bali.jpg
 ┃ ┣ 🖼️ konfigurasi_routing_pada_router_bandung.jpg
 ┃ ┣ 🖼️ konfigurasi_routing_pada_router_jakarta.jpg
 ┃ ┗ 🖼️ konfigurasi_routing_pada_router_tegal.jpg
 ┣ 📜 simulasi_jaringan_multi-branch.pkt      # File utama Cisco Packet Tracer
 ┗ 📜 README.md
