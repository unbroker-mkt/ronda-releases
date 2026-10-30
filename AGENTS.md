# Instrucciones para agentes

## Cortar videos: siempre con video-use

Para **cortar cualquier video** (sacar silencios, tiempos muertos o tomas repetidas, o armar el primer corte de
un crudo hablado), usar **siempre** la skill **video-use**. Está en hey404-mkt:
[`.agents/skills/video-use`](https://github.com/unbroker-mkt/hey404-mkt/tree/main/.agents/skills/video-use).
Leer antes `NOTAS-HEY404.md`, que tiene la instalación y los cuidados.

- No cortar a mano con ffmpeg ni con detección de silencios propia.
- Las skills de estilo arrancan desde el corte de video-use.
