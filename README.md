<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:8B5CF6,55:6D28D9,100:06B6D4&text=Joseph%20S%C3%A1nchez&fontColor=FFFFFF&fontSize=58&fontAlignY=38&desc=CTO%20%26%20AI%20Lead%20%C2%B7%20Fundador%20de%20InfiniHon&descAlignY=60&descSize=20&animation=fadeIn" width="100%" alt="Joseph Sánchez — CTO & AI Lead"/>

<a href="https://github.com/sarch-codelab">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3200&pause=900&color=8B5CF6&center=true&vCenter=true&width=760&height=40&lines=Del+caos+al+control.;IA+aplicada+a+la+gesti%C3%B3n+empresarial.;SaaS+multi-tenant+%C2%B7+offline-first+%C2%B7+facturaci%C3%B3n+SAR.;Construido+desde+Honduras+para+Latinoam%C3%A9rica." alt="Typing animation"/>
</a>

<br/>

<a href="https://portal-pilot.vercel.app"><img src="https://img.shields.io/badge/Portal_Pilot-Ver_demo-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/sarch-codelab?tab=followers"><img src="https://img.shields.io/github/followers/sarch-codelab?label=Seguidores&style=for-the-badge&logo=github&logoColor=white&color=06B6D4&labelColor=0D1117"/></a>
<a href="https://github.com/sarch-codelab?tab=repositories"><img src="https://img.shields.io/badge/Repositorios-12-F59E0B?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117"/></a>
<img src="https://img.shields.io/badge/Honduras-%F0%9F%87%AD%F0%9F%87%B3-0051BA?style=for-the-badge&labelColor=0D1117"/>

</div>

<br/>

> *"Transformando la gestión empresarial a través de tecnología inteligente."*

Soy **CTO y AI Lead**: arquitecto y desarrollador FullStack. Diseño plataformas **SaaS multi-tenant**, sistemas de **facturación electrónica** y **asistentes de IA** que se integran a cada módulo del negocio, pensados para la realidad de Latinoamérica: conectividad inestable, normativa local y equipos pequeños que necesitan hacer mucho.

<br/>

## ⚡ En qué me enfoco

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🤖 IA aplicada</h3>
      Asistentes con LLMs en cada módulo, vía <b>Groq API</b> y modelos locales para operar sin depender de la nube.
    </td>
    <td width="33%" valign="top">
      <h3>🏢 Multi-tenant</h3>
      Aislamiento de datos por empresa con <b>Row Level Security</b> sobre PostgreSQL.
    </td>
    <td width="33%" valign="top">
      <h3>📴 Offline-first</h3>
      Apps que siguen vendiendo sin internet: cola offline y <b>upsert idempotente</b> al reconectar.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🧾 Facturación SAR</h3>
      Cumplimiento de la normativa fiscal de Honduras integrado al flujo de venta.
    </td>
    <td valign="top">
      <h3>🔐 Seguridad enterprise</h3>
      <b>2FA</b>, roles y permisos, y trazabilidad de cada operación.
    </td>
    <td valign="top">
      <h3>⚙️ Automatización RPA</h3>
      Procesos comerciales automatizados con evidencia verificable.
    </td>
  </tr>
</table>

<br/>

## 🚀 Proyecto principal

<div align="center">

### 🧠 Portal Pilot
**Plataforma SaaS con IA para la gestión de negocios**<br/>
*"Del caos al control"*

<a href="https://portal-pilot.vercel.app"><img src="https://img.shields.io/badge/VER_DEMO-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/sarch-codelab/portalpilot"><img src="https://img.shields.io/badge/C%C3%93DIGO-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

ERP comercial integral para **pulperías, supermercados, distribuidoras y cadenas multi-sucursal**, con un asistente de IA en cada módulo.

| | Módulo | Qué resuelve |
|---|---|---|
| 🛒 | **POS** | Ventas con lector de códigos de barras |
| 📦 | **Inventario** | Multi-bodega y multi-sucursal |
| 🧾 | **Facturación** | Electrónica SAR (Honduras) |
| 👥 | **CRM** | Clientes y seguimiento comercial |
| 💰 | **Contabilidad** | Control financiero integrado |
| 👔 | **RRHH** | Gestión de personal |
| 🤖 | **Asistentes IA** | Ayuda contextual en cada módulo |

### 🏗️ Arquitectura

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1E1B2E','primaryBorderColor':'#8B5CF6','primaryTextColor':'#F5F3FF','lineColor':'#06B6D4','fontFamily':'monospace'}}}%%
flowchart LR
  A["📱 App Flutter<br/>Android · iOS · Web · Windows"] -->|escribe siempre local| B[("SQLite · Drift<br/>offline-first")]
  B -->|cola offline<br/>upsert idempotente| C["⚙️ API<br/>Node.js + Express"]
  C --> D[("Supabase · PostgreSQL<br/>multi-tenant + RLS")]
  C --> E["🤖 Capa de IA<br/>Groq · LLMs"]
  F["🔐 2FA · Roles"] -.-> C
```

<br/>

## 🧪 Otros proyectos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📱 Portal Pilot App</h3>
      App <b>Flutter offline-first</b> para Android, iOS, Web y Windows. Base local con SQLite/Drift, cola offline y sincronización en la nube con IA integrada.<br/><br/>
      <a href="https://github.com/sarch-codelab/portalpilot-app"><img src="https://img.shields.io/badge/Ver_c%C3%B3digo-181717?style=flat-square&logo=github"/></a>
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
      <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>🛰️ Alerta Sula</h3>
      Sistema de alertas en tiempo real para la red hidrometeorológica de Honduras, con simuladores interactivos (v1–v4) y API serverless.<br/><br/>
      <a href="https://github.com/sarch-codelab/alerta-sula"><img src="https://img.shields.io/badge/Ver_c%C3%B3digo-181717?style=flat-square&logo=github"/></a>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
      <img src="https://img.shields.io/badge/Serverless-06B6D4?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🌐 InfiniHon Honduras</h3>
      Sitio web oficial de la marca: presencia digital corporativa con diseño cuidado.<br/><br/>
      <a href="https://github.com/sarch-codelab/infinihon"><img src="https://img.shields.io/badge/Ver_c%C3%B3digo-181717?style=flat-square&logo=github"/></a>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
    </td>
    <td valign="top">
      <h3>📂 Todo el código</h3>
      12 repositorios públicos y creciendo.<br/><br/>
      <a href="https://github.com/sarch-codelab?tab=repositories"><img src="https://img.shields.io/badge/Explorar_repositorios-8B5CF6?style=flat-square&logo=github&logoColor=white"/></a>
    </td>
  </tr>
</table>

<br/>

## 🛠️ Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=flutter,dart,nodejs,express,supabase,postgres,vercel,html,css,js,git,github&perline=12" alt="Stack tecnológico"/>

<br/><br/>

<img src="https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Llama-8B5CF6?style=for-the-badge&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/Mixtral-FF6B35?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Codemagic-34B7F1?style=for-the-badge&logo=codemagic&logoColor=white"/>
<img src="https://img.shields.io/badge/NocoDB-0078D4?style=for-the-badge&logoColor=white"/>

</div>

<br/>

## 📊 Actividad

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=sarch-codelab&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117" alt="Estadísticas"/>
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sarch-codelab&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true&bg_color=0D1117" alt="Lenguajes"/>

<br/>

<img src="https://streak-stats.demolab.com?user=sarch-codelab&theme=midnight-purple&hide_border=true&background=0D1117&ring=8B5CF6&fire=F59E0B&currStreakLabel=06B6D4" alt="Racha"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sarch-codelab&bg_color=0D1117&color=8B5CF6&line=06B6D4&point=FFFFFF&area=true&hide_border=true" width="95%" alt="Gráfico de contribuciones"/>

</div>

<br/>

## 👥 Equipo

<div align="center">

| 🧠 **Joseph Sánchez** | 🎯 **Amy Fajardo** | 🛡️ **Sofia Guzman** | ⚙️ **Jose Carcamo** |
|:---:|:---:|:---:|:---:|
| **CTO & AI Lead** | **CEO & Fundador** | **Head of Security** | **Desarrollo & RPA** |
| FullStack · IA Cloud · Groq API | Arquitectura · Cloud · Estrategia | Ciberseguridad · 2FA · Auth | Backend API · RPA · Trazabilidad |

</div>

<br/>

## 📫 Hablemos

¿Quieres automatizar tu negocio, probar Portal Pilot o colaborar? Escríbeme o échale un vistazo a la demo.

<div align="center">

<a href="https://portal-pilot.vercel.app"><img src="https://img.shields.io/badge/Portal_Pilot-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://github.com/sarch-codelab"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/>

<sub>Innovación · Calidad · Excelencia &nbsp;|&nbsp; Construido con pasión en Honduras 🇭🇳 para el mundo</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:06B6D4,50:6D28D9,100:8B5CF6&section=footer" width="100%" alt=""/>

</div>
