FROM alpine:latest

# Install FFmpeg
RUN --mount=type=cache,target=/var/cache/apk apk add ffmpeg

# Set the working directory
WORKDIR /videos

# Entrypoint
CMD ["sh"]
