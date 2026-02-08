# CLAUDE.md

ClueBot NG Bot - Wikipedia vandalism detection bot.

## Stack
- PHP 7.x+

## Test
```bash
# Syntax check
find . -name "*.php" -exec php -l {} \;

# Run tests (if available)
composer test
```

## Note
This is a Wikipedia bot. Configuration in cluebot-ng.config.php is sensitive and should not be committed.
