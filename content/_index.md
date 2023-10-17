---
title: My Site
layout: hextra-home
---
{{< hextra/hero-badge >}}
  <div class="w-2 h-2 rounded-full bg-primary-400"></div>
  <span>Maintenance</span>
  {{< icon name="speakerphone" attributes="height=14" alt_text="test" >}}
{{< /hextra/hero-badge >}}

<div class="mt-6 mb-6">
{{< hextra/hero-headline >}}
  My Site&nbsp;<br class="sm:block hidden" />
{{< /hextra/hero-headline >}}
</div>


<div class="mb-12">
{{< hextra/hero-subtitle >}}
  Personal Web of Wahyu&nbsp;<br class="sm:block hidden" />yang dibuat saat bengong
{{< /hextra/hero-subtitle >}}
</div>

<div class="mb-6">
{{< hextra/hero-button text="Donate for starling" link="#">}}
</div>

<div class="mt-6"></div>

{{< hextra/feature-grid >}}
  {{< hextra/feature-card
    title="Summary"
    subtitle="Saya Wahyudin, seorang mahasiswa semester 7 di Universitas Ibn Khaldun Bogor. Saya memiliki pengalaman bekerja sebagai IT Support melalui Program Internship di beberapa perusahaan."
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}
  {{< hextra/feature-card
    title="Experience"
    subtitle="• Galang System Infotama <br> • PT.Pertamina Training & Consulting <br> • PT.Mitra AdiPerkasa "
    style="background: radial-gradient(ellipse at 50% 80%,rgba(142,53,74,0.15),hsla(0,0%,100%,0));"
  >}}
  {{< hextra/feature-card
    title="Skills"
    subtitle="• Software Troubleshoot <br> • Hardware Troubleshoot <br> • Microsoft Office <br> .... "
    style="background: radial-gradient(ellipse at 50% 80%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}
  {{< hextra/feature-card
    title="And Much More..."
    icon="sparkles"
    subtitle="Mungkin nanti jika ada.."
  >}}
{{< /hextra/feature-grid >}}

{{< cards >}}
  {{< card link="project" title="Project" icon="collection" >}}
  {{< card link="about" title="About" icon="user" >}}
{{< /cards >}}
