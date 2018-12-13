# Tugas TCC tentang IaC

![](https://docs.microsoft.com/en-us/azure/devops/learn/_img/infrastructureascode_600x300-3.png)

Infrastructure as Code adalah proses penyediaan IT infrastruktur dimana sistem dibangun dan dikelola melalui kode secara automasi (otomatis), bukan secara manual. Atau bisa disebut juga bahasa kerennya Programmable Infrastructure. Infrastruktur TI yang dikelola oleh ini terdiri dari kedua peralatan fisik seperti server bare-metal serta mesin virtual dan sumber daya konfigurasi terkait.
Pendekatan IaC dipromosikan untuk komputasi awan, yang terkadang dipasarkan sebagai IaaS. IaC mendukung IaaS.

IaC tumbuh sebagai respon terhadap kesulitan yang ditimbulkan dari dua bagian teknologi - utilitas komputasi dan kerangka web generasi kedua. Hal ini menimbulkan masalah skala besar bagi banyak perusahaan yang sebelumnya hanya disaksikan oleh perusahaan besar. Pada tahun 2006, khusus peluncuran Cloud Compute Elastic Cloud dari Layanan Web dan versi 1.0 dari Ruby on Rails beberapa bulan sebelumnya.

Nilai IaC dapat dibagi menjadi tiga kategori yang dapat diukur: Biaya (pengurangan), kecepatan (eksekusi lebih cepat) dan risiko (menghapus kesalahan dan pelanggaran keamanan).

Secara umum ada tiga pendekatan untuk IaC: deklaratif (fungsional) vs. imperatif (prosedural) vs. cerdas (sadar lingkungan). Perbedaan antara pendekatan deklaratif, imperatif dan cerdas pada dasarnya adalah 'apa' melawan 'bagaimana 'melawan' why '.

Ada dua metode IaC: 'push' dan 'pull'. Perbedaan utama adalah cara server diberitahu cara mengkonfigurasi. Dalam metode pull, server yang akan dikonfigurasi akan menarik konfigurasinya dari server pengontrol. Dalam metode push, server pengendali mendorong konfigurasi ke sistem tujuan.

Ada banyak alat yang memenuhi kemampuan otomatisasi infrastruktur dan menggunakan IaC. Secara garis besar, kerangka kerja apa pun, atau alat yang melakukan perubahan atau mengkonfigurasi infrastruktur secara deklaratif atau imperatif berdasarkan pendekatan terprogram dapat dianggap IaC. Secara tradisional, server (lifecycle) otomatisasi dan alat manajemen konfigurasi digunakan untuk mencapai IaC, sekarang perusahaan menggunakan alat otomatisasi konfigurasi berkelanjutan atau kerangka IaC yang berdiri sendiri, seperti Microsoft PowerShell DSC.

<table class="wikitable">
<tbody><tr>
<th>Tool</th>
<th>Released by</th>
<th>Method</th>
<th>Approach</th>
<th>Written in
</th></tr>
<tr>
<th><a href="/wiki/Ansible_(software)#Ansible_Tower" title="Ansible (software)">Ansible Tower</a> / Ansible
</th>
<td><a href="/wiki/RedHat" class="mw-redirect" title="RedHat">RedHat</a>
</td>
<td>Push
</td>
<td>Declarative and imperative
</td>
<td><a href="/wiki/Python_(programming_language)" title="Python (programming language)">Python</a>
</td></tr>
<tr>
<th><a href="/wiki/CFEngine" title="CFEngine">CFEngine</a>
</th>
<td>CFEngine
</td>
<td>Pull
</td>
<td>Declarative
</td>
<td>-
</td></tr>
<tr>
<th><a href="/wiki/Chef_(software)" title="Chef (software)">Chef</a>
</th>
<td>Chef
</td>
<td>Pull
</td>
<td>Declarative and imperative
</td>
<td><a href="/wiki/Ruby_(programming_language)" title="Ruby (programming language)">Ruby</a>
</td></tr>
<tr>
<th><a href="/wiki/Otter_(software)" title="Otter (software)">Otter</a>
</th>
<td><a href="/wiki/Inedo" title="Inedo">Inedo</a>
</td>
<td>Push
</td>
<td>Declarative and imperative
</td>
<td>-
</td></tr>
<tr>
<th><a href="/wiki/Puppet_(software)" title="Puppet (software)">Puppet</a>
</th>
<td>Puppet
</td>
<td>Pull
</td>
<td>Declarative
</td>
<td><a href="/wiki/Ruby_(programming_language)" title="Ruby (programming language)">Ruby</a>
</td></tr>
<tr>
<th><a href="/wiki/SaltStack" class="mw-redirect" title="SaltStack">SaltStack</a>
</th>
<td>SaltStack
</td>
<td>Push and Pull
</td>
<td>Declarative and imperative
</td>
<td><a href="/wiki/Python_(programming_language)" title="Python (programming language)">Python</a>
</td></tr>
<tr>
<th><a href="/wiki/Terraform_(software)" title="Terraform (software)">Terraform</a>
</th>
<td><a href="/wiki/HashiCorp" title="HashiCorp">HashiCorp</a>
</td>
<td>Push
</td>
<td>Declarative
</td>
<td><a href="/wiki/Go_(programming_language)" title="Go (programming language)">Go</a>
</td></tr>
</tbody></table>

# Untuk Instalasi
```
root@ubuntuc:/home/vagrant# sudo apt-get update
root@ubuntuc:/home/vagrant# apt-get install ansible
```
