[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/CU6l4amx)

## OpenAPI Documentation

This project exposes OpenAPI 3 documentation for all REST endpoints.

- Swagger UI: `/swagger-ui/index.html`
- OpenAPI JSON: `/v3/api-docs`

### Authentication in Swagger UI

Protected endpoints use JWT bearer authentication (`bearerAuth`).

1. Login via `POST /api/v1/auth/login` and copy `accessToken`.
2. In Swagger UI, click **Authorize**.
3. Paste token as: `Bearer <accessToken>`.
4. Call secured endpoints such as `/api/v1/me`, `/api/v1/roles`, and `/api/v1/hotels`.
