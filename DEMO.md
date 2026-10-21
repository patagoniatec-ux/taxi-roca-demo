# Roca · Taxi y envíos — Prototipo

Demo estática sin dependencias. Abrir index.html o publicar con GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Probar el circuito
1. En Pasajero, elegir taxi o paquete, origen y destino distintos y confirmar.
2. Cambiar a Conductor y aceptar el pedido.
3. Confirmar llegada, ingresar el código ficticio 4827 e iniciar.
4. Finalizar el viaje. Para paquete, confirmar entrega con 7391.
5. Registrar un reclamo desde Pasajero y resolverlo desde Administrador.

## Límites
Todos los datos y tarifas son ficticios. El mapa es un esquema, sin GPS ni rutas geográficas. El movimiento depende de los cambios de estado manuales. No hay cuentas, verificación documental, autenticación, pagos, atención de emergencias ni sincronización entre dispositivos. Las vistas son públicas y los datos se pierden al recargar. No introducir datos personales reales. El administrador único es conceptual; no existe control de acceso en esta demo.

## Antes de una operación real
Definir reglas con el cliente, tarifas y cobertura, requisitos de conductores y vehículos, cancelaciones, incidentes y paquetería. Implementar backend, asignación atómica, permisos, autenticación y recuperación, privacidad y retención de datos, monitoreo y revisión profesional de seguridad. Probar con usuarios y dispositivos reales antes del piloto.
