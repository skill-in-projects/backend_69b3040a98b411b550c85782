# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b3040a98b411b550c85782_user:5PfQG81EY%5EJImmooxBEN%2Ac7eHOXscmqw@ep-bitter-poetry-aela5per.c-2.us-east-2.aws.neon.tech:5432/AppDB_69b3040a98b411b550c85782?sslmode=require`

## Web API

**WebApi URL:** https://webapi69b3040a98b411b550c85782-production.up.railway.app

**Swagger API Tester URL:** https://webapi69b3040a98b411b550c85782-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
