# Kitsu for TrueNAS SCALE

Open-source collaboration platform for animation and VFX productions.

## Requirements
- TrueNAS SCALE 22.02 or later
- At least 4GB RAM
- Persistent storage for database and media files

## Configuration
- **Web Port**: Default is 8080
- **Database Password**: Set a secure password
- **Secret Key**: Generated automatically or set manually

## Storage
This app requires the following datasets to be created:
- `/mnt/DATA2/kitsu/postgres` - PostgreSQL database
- `/mnt/DATA2/kitsu/preview` - Preview files
- `/mnt/DATA2/kitsu/thumbnails` - Thumbnail files
