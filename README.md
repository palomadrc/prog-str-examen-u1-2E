# Examen U1 — Git: ramas, conflicto y merge 


## Reglas obligatorias
1) **NO** se permite merge a `main`.
2) Ramas obligatorias (desde `main`):
- `nombre-apellido/develop`
- `nombre-apellido/merge`

> Ejemplo: `ana-lopez/develop` y `ana-lopez/merge`

## Línea objetivo (debe provocar el conflicto)
Para provocar conflicto vas a editar la **misma línea** en ambas ramas.

**INSTRUCCIÓN IMPORTANTE:**
- **Edita SOLO esta línea**. No la copies, no la muevas, no la dupliques.

**LÍNEA OBJETIVO (NO BORRAR):**
`CODIGO_CONTROL: merge`

## Pasos obligatorios
1) Clona el repo y ábrelo en IntelliJ.
2) Confirma que estás en `main`.
3) Crea y cámbiate a: `nombre-apellido/develop`
4) En `nombre-apellido/develop`:
   - Cambia la línea objetivo a: `CODIGO_CONTROL: develop`
   - Commit: `develop: cambio para conflicto`
   - Push.
5) Regresa a `main`.
6) Crea y cámbiate a: `nombre-apellido/merge`
7) En `nombre-apellido/merge`:
   - Cambia la línea objetivo a: `CODIGO_CONTROL: merge`
   - Commit: `merge: cambio para conflicto`
   - Push.
8) Estando en `nombre-apellido/merge`, mergea:
   - `nombre-apellido/develop` ➜ `nombre-apellido/merge`
9) Resuelve el conflicto dejando el resultado final EXACTO así:
   - `CODIGO_CONTROL: RESUELTO (develop + merge)`
10) Finaliza el merge (commit si aplica) y push.

## Evidencias a entregar
1) Link al repo.
2) Evidencia de ambas ramas (captura).
3) Evidencia del merge en `nombre-apellido/merge` (captura).
4) Evidencia de que `main` quedó intacta (sin merges).
