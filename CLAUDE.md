<laravel-boost-guidelines>
# Laravel Application - Enhanced Memory System

This repository contains a Laravel application. Complete the following setup before working on the user's request.

## Project Memory Overview

This CLAUDE.md file contains comprehensive project memory to guide the agent, conserve tokens, and provide instant access to directory purposes and workflow guidance.

## Prerequisites

Verify that PHP and Composer are available:

```sh
php -v
composer -V
```

If either command is unavailable, detect the user's operating system and install the prerequisites with the appropriate command:

macOS:

```sh
/bin/bash -c "$(curl -fsSL https://php.new/install/mac/8.5)"
```

Windows PowerShell:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows/8.5'))
```

Linux:

```sh
/bin/bash -c "$(curl -fsSL https://php.new/install/linux/8.5)"
```

After installation, ask the user to restart their terminal. If the agent needs the restarted shell to continue, ask the user to reopen their terminal and rerun their original prompt.

## Agent Setup

Install Laravel Boost from the application root before making application changes:

```sh
composer require laravel/boost --dev
php artisan boost:install
```

Boost replaces these bootstrap instructions with guidelines tailored to the application. After installation, read `AGENTS.md` again and continue with the user's original request using the generated guidelines.

---

# Directory Memory System

## 🚀 PROJECT OVERVIEW
**Type**: Laravel Boost Application  
**Status**: Initial Setup Phase (awaiting Laravel Boost installation)

## 📁 DIRECTORY MEMORY

### 1. `app/` - Application Core
**Purpose**: Central application logic and business rules
**Subdirectories**:
- `Http/` - HTTP request handling, controllers, middleware
- `Models/` - Eloquent models and database relationships  
- `Providers/` - Service providers for framework features

**Key Files**: Controllers, Models, Requests, Events, Listeners

### 2. `config/` - Application Configuration
**Purpose**: Runtime configuration management
**Key Files**:
- `app.php` - Application settings and providers
- `auth.php` - Authentication configuration
- `database.php` - Database connection settings
- `session.php` - Session management
- `queue.php` - Job queue configuration
- `cache.php` - Caching configuration

### 3. `database/` - Data Storage
**Purpose**: Database management and migrations
**Structure**:
- `database.sqlite` - SQLite database file
- `migrations/` - Schema changes and database structure
- `seeders/` - Initial data population
- `factories/` - Model data generators (for testing)

### 4. `public/` - Web Assets
**Purpose**: Publicly accessible files and frontend entry point
**Key Files**:
- `index.php` - Laravel frontend bootstrap
- `.htaccess` - Apache web server configuration
- Static assets (when added)

### 5. `routes/` - URL Routing
**Purpose**: Application URL routing and HTTP endpoint definition
**Key Files**:
- `web.php` - Web application routes
- `console.php` - Artisan command routes

### 6. `storage/` - File Storage
**Purpose**: File uploads, caches, and logs
**Subdirectories**:
- `app/` - User uploaded files
- `framework/` - Framework-generated files (views, caches)
- `logs/` - Application error and access logs

### 7. `tests/` - Quality Assurance
**Purpose**: Application testing and validation
**Structure**:
- `Feature/` - Feature-based integration tests
- `Unit/` - Unit tests for individual components
- `TestCase.php` - Base test case class

## 💡 TOKEN CONSERVATION STRATEGIES

### Quick Reference Commands
```bash
# Check directory purposes
ls -la app/ config/ database/ public/ routes/ storage/ tests/

# View key configuration files
cat config/app.php config/database.php config/session.php

# Check current setup status
cat CLAUDE.md AGENTS.md
```

### Usage Patterns
**Instead of**: `What does the app/ directory contain?`
**Use**: Directory memory for instant purpose lookup

**Instead of**: `What does config/app.php do?`
**Use**: Directory memory points to relevant configuration details

**Instead of**: `How do I set up Laravel?`
**Use**: Project memory provides exact setup sequence

## 🔄 WORKFLOW MEMORY

### Current Phase: Laravel Boost Setup
1. **Prerequisites Check**: Verify PHP and Composer
2. **Laravel Boost Installation**: `composer require laravel/boost --dev` + `php artisan boost:install`
3. **Post-Setup**: Read AGENTS.md for agent-specific guidance

### Memory Access Rules
- **Directory inquiries**: Use directory memory system
- **Workflow questions**: Follow established workflow sequence
- **Configuration details**: Reference config/ directory memory
- **Setup requirements**: Follow Laravel Boost sequence

## 🎯 AGENT GUIDANCE

This memory system provides:
- ✅ Instant directory purpose lookup
- ✅ Token-conserving reference patterns
- ✅ Standardized workflow navigation
- ✅ Clear progression from setup to implementation

**Memory is actively maintained** - updates will be reflected in future sessions.

---

# Laravel Boost Guidelines

## Project Type
This is a Laravel Boost application requiring specific initialization before any development work can proceed.

## Execution Protocol
1. Verify development environment (PHP, Composer)
2. Install Laravel Boost via composer
3. Run boost:install artisan command
4. Review AGENTS.md for agent-specific instructions
5. Continue with original user request

## Important Notes
- Do not proceed with development until Laravel Boost is installed
- Follow the exact setup sequence to ensure proper project initialization
- Use this CLAUDE.md as the primary reference for project structure and workflow
</laravel-boost-guidelines>
