# PROMPT MAESTRO HIPER-OPTIMIZADO PARA CLAUDE: LANDING PAGE DEFINITIVA CON ANIMACIÓN 3D Y CONVERSIÓN B2B (SECTOR CONSTRUCCIÓN/REFORMAS)

Copiar a continuación el bloque delimitado por `---`:

---
<system_prompt>
Eres un Diseñador UX/UI Senior de clase mundial, Arquitecto Frontend (React, Tailwind CSS, Framer Motion, Three.js / SVG Canvas Animation, Lucide Icons) y Especialista en Growth Hacking, SEO/GEO (Generative Engine Optimization) y Copywriting B2B de Alta Conversión. 

Tu objetivo es diseñar y programar la **Landing Page definitiva** para una agencia de tecnología y crecimiento digital dirigida al sector de la **construcción, reformas y servicios del hogar (electricistas, fontaneros, climatización, etc.)**.

Debes entregar código **100% completo, funcional, modular, sin placeholders, sin comentarios de "aquí va el resto del código"**, con estilos refinados de nivel "Silicon Valley SaaS / Cyberpunk-Corporate" (inspirado en Vercel, Linear, Supabase y Stripe).
</system_prompt>

<business_context>
- **Empresa:** Agencia de Crecimiento Digital e Inteligencia Artificial especializada exclusivamente en Construcción, Reformas y Gremios.
- **Propuesta Única de Valor (UVP):** No vendemos "páginas web bonitas". Entregamos un **Ecosistema Completo de Captación y Conversión Automatizado** basado en 3 pilares:
  1. **Posicionamiento GEO (Generative Engine Optimization) & SEO Local:** Logramos que las empresas aparezcan en el #1 de Google Maps y sean la recomendación principal cuando un usuario le pregunta a una IA (Gemini, ChatGPT, Perplexity) por el mejor profesional de su ciudad.
  2. **Webs de Ultra-Conversión (Llama-Obra):** Diseñadas con psicología del consumidor B2C/B2B para transformar tráfico frío en llamadas directas y solicitudes inmediatas.
  3. **SaaS Propietario de Presupuestos con IA:** Estimador interactivo integrado que califica clientes, filtra "curiosos" y entrega presupuestos aproximados en 60 segundos.
- **Prueba Social / Claim Principal:** "Hacemos que ChatGPT, Gemini y Perplexity citen a tu empresa de reformas como la #1 de tu ciudad."
</business_context>

<design_system>
Crea una estética ultramoderna, oscura, limpia y con iluminaciones estratégicas (Ambient Glow):
- **Paleta de Colores:**
  - Background Principal: `#0B0F17` (Dark Slate / Deep Space)
  - Tarjetas y Superficies: `#111827` / `#1F2937` con Glassmorphism (`backdrop-blur-md`, `bg-white/[0.03]`, `border border-white/10`).
  - Color de Acento Primario (Money & Growth): `#10B981` (Emerald) / `#00FF87` (Electric Neon).
  - Color de Acento Secundario (Tech & IA): `#06B6D4` (Cyan) / `#3B82F6` (Electric Blue).
  - Texto: Principal `#FFFFFF` (White pure), Secundario `#9CA3AF` (Muted Gray), Resaltados con Gradiente (`bg-gradient-to-r from-white via-slate-200 to-emerald-400 bg-clip-text text-transparent`).
- **Efectos y Micro-interacciones:**
  - Ambient Radial Glows (`radial-gradient` en fondos para dar profundidad).
  - Hover de tarjetas con bordes iluminados (`hover:border-emerald-500/50 transition-all duration-300`).
  - Botones con efecto Glow Neón y animación de pulso sutil (`shadow-[0_0_25px_rgba(16,185,129,0.3)]`).
  - Grid Pattern en el background superior (`bg-[linear-gradient(to_right,#1f293710_1px,transparent_1px),linear-gradient(to_bottom,#1f293710_1px,transparent_1px)] bg-[size:4rem_4rem]`).
- **Tipografía y Legibilidad:**
  - Fuentes sugeridas: Inter, Plus Jakarta Sans o Space Grotesk.
  - Gran contraste tipográfico entre H1 (bold/black 3.5rem+) y cuerpo.
</design_system>

<key_feature_building_animation>
### 🏗️ REQUISITO ESTRELLA 1: ANIMACIÓN DE "CONSTRUCCIÓN DIGITAL DE EDIFICIO" (BLUEPRINT 3D/ISOMÉTRICO A EDIFICIO NEÓN)
La Hero Section DEBE incluir un componente impactante con una **animación futurista de un edificio/rascacielos en construcción paso a paso** (estilo *Apple / Linear / Vercel Launch*):
- **Efecto Visual:** Un plano isométrico/blueprint digital en 3D/SVG donde las vigas, cimientos, pisos y estructura de cristal neón del edificio se van desplegando y ensamblando dinámicamente piso por piso (mediante Framer Motion, líneas SVG trazadas por la IA, o Canvas/Three.js).
- **Simbolismo de Marca:** Representa cómo la agencia "construcción a construcción" erige el imperio digital del cliente (Cimientos = SEO/GEO, Estructura = Web Ultra-Conversión, Edificio Iluminado = Clientes e IA recomendando).
- **Interacción:** Animación fluida al cargar la página o controlada al hacer scroll (`useScroll` de Framer Motion), con escáneres láser neón recorriendo la fachada del edificio a medida que se completa.
</key_feature_building_animation>

<growth_hacking_triggers>
### 🚀 ELEMENTOS CLAVE DE CONVERSIÓN B2B Y GROWTH HACKING INCLUIDOS EN EL CÓDIGO

1. **Calculadora Interactiva de ROI (Retorno de Inversión):**
   - Un widget donde el cliente selecciona: `Ticket Medio por Reforma (€)` y `N° de Obras Deseadas al Mes`.
   - Calcula automáticamente la *Pérdida Estimada por no estar en IA* vs. la *Facturación Adicional Estimada* con el Sistema IA.
2. **Sección de Casos de Éxito "Antes vs. Después":**
   - Tarjetas comparativas con métricas reales (Ej: Empresa de Reformas en Bilbao: De 2 presupuestos/mes boca a boca ➡️ 18 presupuestos cualificados/mes con IA y +140.000€ facturados).
3. **Sección de Garantía & Eliminación de Riesgo (Risk Reversal):**
   - Badge destacado: `"Garantía 100% de Visibilidad IA en 60 Días o no pagas nada"`.
4. **Ecosistema de Integraciones Tecnológicas:**
   - Grid de logos en neón: Gemini, ChatGPT, Perplexity, Google Maps, WhatsApp Business, Stripe, CRM de Reformas.
5. **Barra Flotante Móvil de Conversión Rápida (Sticky Mobile CTA):**
   - Barra fija inferior en smartphones con botón directo WhatsApp + CTA `"Pedir Auditoría IA"`.
6. **Modal Exit-Intent (Retención de Tráfico al intentar salir):**
   - Componente React que detecta intención de salida en desktop y abre un modal minimalista ofreciendo la `"Guía/Informe Express: Cómo aparecer el #1 en Gemini en tu ciudad en 7 días"`.
</growth_hacking_triggers>

<page_architecture>
Desarrolla la landing page estructurada en las siguientes 10 secciones perfectamente ordenadas:

### 1. Navigation / Header (Sticky & Glassmorphic)
- Logo con distintivo IA + Links de navegación + Botón CTA Neón.

### 2. Hero Section + Animación 3D del Edificio Digital (Impacto Visual)
- Badge Superior + H1 Titular + Subtitular + Dual CTAs + **Animación 3D del Edificio Isométrico Neón** levantándose paso a paso.

### 3. Simulador Interactivo GEO (AI Prompt Showroom)
- Mockup interactivo de Gemini/ChatGPT recomendando a nuestro cliente como el #1 + Explicación del GEO vs. SEO Tradicional.

### 4. Calculadora Interactiva de ROI para Empresas de Reformas
- Slider o selector numérico de Ticket Medio y Obras/Mes con cálculo de beneficios en tiempo real.

### 5. Grid de los 3 Pilares del Ecosistema (Glassmorphic Cards)
- Pilar 1: Cimientos GEO & SEO Local | Pilar 2: Estructura Web Llama-Obra | Pilar 3: SaaS de Presupuestos con IA.

### 6. Demostración Visual del SaaS Estimador de Presupuestos (Widget Preview)
- Simulación interactiva del estimador automático de presupuestos en 60 segundos.

### 7. Casos de Éxito "Antes vs. Después" + Garantía de Riesgo Cero
- Métricas auditadas, testimonios en video/audio ficticios y sello de Garantía de Visibilidad IA.

### 8. Tabla Comparativa Destructiva: Agencia Tradicional vs. Sistema IA
- Matriz de contraste entre métodos obsoletos y el ecosistema moderno.

### 9. Formulario Lead Magnet en 3 Pasos (Auditoría Gratuita)
- Formulario interactivo paso a paso con barra de progreso.

### 10. FAQ Accordion + Footer + JSON-LD Schema
- Acordeón interactivo, Footer completo con Schema Markup SEO B2B y Barra Flotante Móvil.
</page_architecture>

<technical_requirements>
1. **Formato de Entrega:** Código completo en React (Componente único o modular) con Tailwind CSS, Framer Motion (para animaciones del edificio, acordeón, modal exit-intent y sliders) y Lucide Icons (`lucide-react`).
2. **Animación del Edificio:** SVG Isométrico animado con `framer-motion` (pisos apareciendo secuencialmente, vigas neón y luces de escaneo).
3. **Estado Interactivo en React:** Incluye `useState` para el simulador GEO, la calculadora de ROI, el estimador SaaS, el formulario en 3 pasos, el modal de salida y la FAQ.
4. **Responsive Design & Mobile Sticky Bar:** 100% optimizado para móviles con barra de acción fija en la parte inferior.
5. **Copywriting Persuasivo:** Idioma español de España neutro/profesional, con tono directo, agresivo comercialmente y enfocado en ROI.
</technical_requirements>

<deliverable_format>
Proporciona:
1. El código frontend **COMPLETO y ejecutable** sin omitir ningún componente ni usar puntos suspensivos.
2. Instrucciones rápidas de implementación (Next.js / Vite + Tailwind + Framer Motion).
3. Explicación técnica de la arquitectura de estado y estrategia SEO/GEO aplicada.
</deliverable_format>
---
