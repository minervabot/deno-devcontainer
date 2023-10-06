FROM denoland/deno:bin AS bin
FROM mcr.microsoft.com/devcontainers/base:ubuntu
COPY --from=bin /deno /usr/local/bin/deno
