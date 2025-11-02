# Contraste de Hipótesis para la Media Poblacional

Herramienta interactiva para visualizar y comprender los errores estadísticos en el contraste de hipótesis.

## Características

- **Visualización interactiva** de distribuciones muestrales bajo H₀ y H₁
- **Análisis de errores** Tipo I (α) y Tipo II (β)
- **Cálculo de potencia** del contraste (1-β)
- **Controles dinámicos** para ajustar parámetros en tiempo real
- **Tabla de decisión** con interpretaciones claras

## Instrucciones para subir a GitHub

### 1. Crear el repositorio en GitHub

1. Ve a [GitHub](https://github.com/upocuantitativo)
2. Haz clic en "New repository" (botón verde)
3. Nombre del repositorio: `hipotesis`
4. Descripción: "Herramienta interactiva de Contraste de Hipótesis Estadísticas"
5. Selecciona **Public** (público)
6. **NO** inicialices con README, .gitignore o licencia
7. Haz clic en "Create repository"

### 2. Subir el código (desde esta carpeta)

Ya tienes el repositorio Git inicializado localmente. Solo necesitas ejecutar:

```bash
git remote set-url origin https://github.com/upocuantitativo/hipotesis.git
git push -u origin main
```

Si GitHub te pide autenticación, necesitarás un Personal Access Token:
- Ve a GitHub Settings → Developer Settings → Personal Access Tokens → Tokens (classic)
- Genera un nuevo token con permisos de `repo`
- Usa el token como contraseña cuando Git te lo pida

### 3. Activar GitHub Pages

1. Ve al repositorio en GitHub: `https://github.com/upocuantitativo/hipotesis`
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, busca **Pages**
4. En "Source", selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
5. Haz clic en **Save**
6. Espera 1-2 minutos

### 4. Acceder a tu página

Tu página estará disponible en:
**https://upocuantitativo.github.io/hipotesis/**

## Uso de la Aplicación

### Controles Principales

1. **Tipo de Contraste**: Bilateral o Unilateral
2. **Medias Poblacionales**: μ₀ (bajo H₀) y μ₁ (bajo H₁)
3. **Nivel de Significación (α)**: Probabilidad de Error Tipo I
4. **Tamaño Muestral (n)**: Número de observaciones
5. **Desviación Estándar (σ)**: Variabilidad poblacional

### Interpretación del Gráfico

- **Curva Azul**: Distribución muestral bajo H₀
- **Curva Morada**: Distribución muestral bajo H₁
- **Área Roja**: Error Tipo I (α) - Rechazar H₀ siendo verdadera
- **Área Naranja**: Error Tipo II (β) - No rechazar H₀ siendo falsa
- **Área Verde**: Potencia (1-β) - Rechazar H₀ siendo falsa

## Tecnologías Utilizadas

- React 18
- Recharts (visualización de gráficos)
- Tailwind CSS (estilos)
- Cálculos estadísticos nativos en JavaScript

## Licencia

Proyecto educativo de código abierto.
