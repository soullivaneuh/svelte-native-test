<script>
  import { SocketIO } from 'nativescript-socketio';
  import feathers from '@feathersjs/client';
  // The following import causes the crash:
  import socketio from '@feathersjs/socketio-client';
  import auth from '@feathersjs/authentication-client';
</script>
