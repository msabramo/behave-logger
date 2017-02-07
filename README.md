# behave-logger
####Custom Behave Logger Util
This library provides functionality to log messages to Behave's captured logging.

Usage
-------
    from behave_logger.logger import get_logger
    logger = get_logger(__name__)
    
    logger.info('This is an information message')
